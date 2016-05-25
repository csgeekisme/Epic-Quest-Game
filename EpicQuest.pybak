################################
##LAB 11: STRATEGY GAME PART 1##
################################
#
# Epic Hero travels down the "Road of Amazement" and stumbles upon the entrance of the only structure amidst the open "Glossimer Meadows."
# Epic Hero cautiously enters into the structure.
# Various weapons are displayed on the walls of this single room structure.
# In the midst of the room lies a secret hatch door, beneath it, a stairway down to adventure...
#
#    FOYER (B-1):
#    4 corners, 4 doors...
#    In each room, Epic Hero finds rupees and a piece of the "Key to Freedom."
#    Out jumps Mini Boss, the only thing that stands between Epic Hero and the treasures of the room.
#    Epic Hero must defeat Mini Boss in order to retrieve rupees for replenishing stock or upgrading weaponry.
#    When Mini Boss is defeated, Epic Hero will also receive one of the 4 pieces of the "Key to Freedom."
#    Epic Hero will then have the choice of going to 1 of the 2 adjacent rooms, or return to the first floor to replenish stock or upgrade weaponry.
#    Once all 4 mini bosses have been defeated, Epic Hero will have all 4 pieces needed for the "Key to Freedom."
#    Epic Hero can return to 1st floor to replenish, or move on to B-2 the "Final Fight," where Epic Hero will fight the Mega Boss.
#
#                           ###################
#                           ##      MAP      ##
#                           ###################
#                           ___________________
#                           |                 |
#                           |                 |
#                           |      FIRST      |
#                           |                 |
#                           |       ---       |
#                           |       | |       |
#                           |       ---       |
#                           |                 |
#                           |      FLOOR      |
#                           |     (STORE)     |
#                           |_________________|
#
#        _________________________________________________________
#        |                           |                           |
#        |                           |                           |
#        |                           /                           |
#        |                           /                           |
#        |           ROOM            /           ROOM            |
#        |                           |                           |
#        |            02       ______|______      03             |
#        |                   _|             |_                   |
#        |                  |                 |                  |
#        |                  |                 |                  |
#        |                  |      FOYER      |                  |
#        |_______----_______|       ---       |_______----_______|
#        |                  |       |_|       |                  |
#        |                  |      (B-1)      |                  |
#        |                  |                 |                  |
#        |                  |_               _|                  |
#        |           ROOM     |_____________|    ROOM            |
#        |                           |                           |
#        |            01             |            04             |
#        |                           /                           |
#        |                           /                           |
#        |                           /                           |
#        |                           |                           |
#        |___________________________|___________________________|
#
#                       ___________________________
#                       |                         |
#                       |                         |
#                       |                         |
#                       |          FINAL          |
#                       |                         |
#                       |          FIGHT          |
#                       |                         |
#                       |          (B-2)          |
#                       |                         |
#                       |                         |
#                       |_________________________|
#
#
import random


#######################################
##Global Variables
programRun = true
name = 'Epic Hero'
defaultHeroHealth = 2500
defaultHeroAttack = 100
heroWeapon = 'None'
weaponAttack = 0
rupeeCount = 1000
potionCount = 0
spellCount = 0
potionHeal = random.randint(25, 75)
spellAttack = random.randint(50, 150)
keyToFreedom = 0
keyPieceCollected1 = false
keyPieceCollected2 = false
keyPieceCollected3 = false
keyPieceCollected4 = false
keyPiece1 = 0
keyPiece2 = 0
keyPiece3 = 0
keyPiece4 = 0
enemyNumber = '0'
enemyHealth1 = 1000
enemyHealth2 = 1500
enemyHealth3 = 2000
enemyHealth4 = 2500
#######################################

#############################
##START EPIC QUEST FUNCTION##
#############################
"""Type epicQuest() into the command area to begin your journey!"""
def epicQuest():
  #welcomeMessage()
  global programRun
  while programRun == true:
    printNow("Your journey awaits you Epic Hero...")
    roadOfAmazement()
  
  printNow("I guess you are not the Epic Hero we thought you were...")
  quit
###########################
##END EPIC QUEST FUNCTION##
###########################

#############################################
##START ROAD OF AMAZEMENT DIALOGUE FUNCTION##
#############################################
def roadOfAmazementDialogue():
  raw_input("Anytime there is a pause in the dialogue, just press Enter to continue.")
  printNow("(Your eyes slowly begin to open, slightly blinded by the sunlight.)")
  raw_input()
  printNow("(You inspect your surroundings, unsure of where you are...)")
  raw_input()
  printNow("(After seeing that you are not injured, you get up and slowly begin walking down the only road in the middle of a field.)")
  raw_input()
  printNow("... ... ... 'Hello Epic Hero!'... (Says a voice from behind you.)")
  raw_input()
  printNow("YOU: 'Who said that?!'")
  raw_input()
  printNow("... 'Over here!'...")
  raw_input()
  printNow("(Epic Hero turns around to see a tiny fairy flying from behind.)")
  raw_input()
  printNow("YOU: 'What is your name?'")
  raw_input()
  printNow("FAIRY: 'My name is Alara. What is your name?'")
  raw_input()
  name = requestString("Please enter your character name: ")
  printNow("YOU: 'My name is " + name + ". Nice to meet you Alara.'")
  raw_input()
  printNow("ALARA: 'The pleasure is mine. I shall call you Epic Hero " + name + "!'")
  raw_input()
  printNow("YOU: 'Huh? No, my name is just " + name + ".'")
  raw_input()
  printNow("YOU: '... Believe me... I'm no epic hero, that's for sure...'")
  raw_input()
  printNow("YOU: '... Where am I Alara?... I'm not sure how I got here... Everything is kind of a blur...'")
  raw_input()
  printNow("ALARA: 'You are on the 'Road of Amazement' in the middle of the beautiful 'Glossimer Meadows,' which is my home.'")
  raw_input()  
  printNow("ALARA: 'I am not sure how you got here either or where you came from.'")
  raw_input()  
  printNow("ALARA: 'I was just out in the field collecting succulent flower nector and berries...'")
  raw_input()  
  printNow("ALARA: '... and... all of sudden... you just appeared out of thin air!'")
  raw_input()  
  printNow("ALARA: 'You fell out of the sky, landed on your head and then passed out.'")
  raw_input()  
  printNow("ALARA: 'I was just coming back from getting a petal of water to splash on your face, but you had already awoken.'")
  raw_input()  
  printNow("YOU: '... That is so weird... I can't remember anything that happened before now.'")
  raw_input()  
  printNow("ALARA: 'If you want my opinion, I think you were sent here for a reason.'")
  raw_input()  
  printNow("YOU: 'Oh, really. Why do you say that?'")
  raw_input()  
  printNow("ALARA: 'A prophecy fortold of an epic hero, coming from a land unknown, who would save us from the evil Dark Lord.'")
  raw_input()  
  printNow("ALARA: 'He is currently locked away in the single standing structure down the road, lying dormant, 2 floors beneath the surface.'")
  raw_input()  
  printNow("ALARA: 'The prophecy says that the Dark Lord will awake and rise up when all is perfect in Galalia.'")
  raw_input()
  printNow("YOU: 'Where is Galalia?'")
  raw_input()
  printNow("ALARA: '... (sniffles)... Glossimer Meadows... (sniffles)... my home... (sniffles)... is in Galalia...'")
  raw_input()
  printNow("YOU: 'What will happen when the Dark Lord awakes? What will happen to Galalia?'")
  raw_input()
  printNow("ALARA: 'He will destroy anyone who stands against him and enslave all others!'")
  raw_input()
  printNow("ALARA: '... (sniffles)... and all this beauty here in Glossimer Meadows, and all of Galalia... (sniffles)... will be burned down.'")
  raw_input()
  printNow("YOU: '... What makes you think I am the one to defeat this Dark Lord?'")
  raw_input()
  printNow("YOU: '... I'm a nobody... always have been...'")
  raw_input()
  printNow("ALARA: 'No! You're wrong! I can see it in your eyes!'")
  raw_input()
  printNow("ALARA: 'You have it in you, you just don't know it yet. You are the Epic Hero of the prophecy.'")
  raw_input()
  printNow("ALARA: 'That's why I called you Epic Hero " + name + "!'")
  printNow("ALARA: 'You can do it. I believe in you!'")
  raw_input()
  printNow("ALARA: 'Will you help us Epic Hero " + name + "? Will you save Galalia?!'")
  raw_input()
  return(name)
###########################################
##END ROAD OF AMAZEMENT DIALOGUE FUNCTION##
###########################################
 
####################################
##START ROAD OF AMAZEMENT FUNCTION##
####################################
def roadOfAmazement():
  roadOfAmazementDialogue()
  myDecision = requestString("Will you save Alara and Galalia?\n" +
                             "(y/n)")
  if myDecision == 'y':
    printNow("ALARA: 'Thank you so much, oh brave Epic Hero " + name + "! Good luck and may the grace of Galalia be with you!'")
    raw_input()
    beginJourney()
  elif myDecision == 'n':
    printNow("ALARA: 'That is really sad to hear... I really thought you were the one, the Epic Hero of the prophecy...'")
    raw_input()
    programRun = false
  else:
    myDecision = requestString("Invalid input! Will you save Alara and Galalia?\n" +
                               "(y/n)")
##################################
##END ROAD OF AMAZEMENT FUNCTION##
##################################

################################
##START BEGIN JOURNEY FUNCTION##
################################
def beginJourney():
  myMovement = requestString("Would you like to proceed down the Road of Amazement toward the structure down the road?\n" +
                             "(forward or exit)")
  if myMovement == 'forward':
    printNow("You have arrived at the structure holding the Dark Lord.")
    raw_input()
    printNow("(You enter with extreme caution.)")
    raw_input()
    theStore()
  elif myMovement == 'exit':
    printNow("Scared already?")
    raw_input()
    roadOfAmazement()
  else:
    myMovement = requestString("Invalid input! Proceed down the Road of Amazement or exit?\n" +
                               "(forward or exit)")
##############################
##END BEGIN JOURNEY FUNCTION##
##############################

######################################
##START WEAPON ATTACK VALUE FUNCTION##
######################################
def weaponAttackValue():
  global heroWeapon
  global weaponAttack
  
  if heroWeapon == 'Dagger':
    weaponAttack = random.randint(5, 50)
  if heroWeapon == 'Short Sword':
    weaponAttack = random.randint(50, 100)
  if heroWeapon == 'Battle Ax':
    weaponAttack = random.randint(100, 150)
  if heroWeapon == 'Long Sword':
    weaponAttack = random.randint(150, 200)
  
  return(weaponAttack)
####################################
##END WEAPON ATTACK VALUE FUNCTION##
####################################

#####################################
##START ENEMY ATTACK VALUE FUNCTION##
#####################################
def enemyAttackValue():
  global enemyNumber
  
  if enemyNumber == '1':
    enemyAttack = 2500 #random.randint(25, 100)
  if enemyNumber == '2':
    enemyAttack = random.randint(50, 150)
  if enemyNumber == '3':
    enemyAttack = random.randint(150, 200)
  if enemyNumber == '4':
    enemyAttack = random.randint(200, 250)
    
  return(enemyAttack)
###################################
##END ENEMY ATTACK VALUE FUNCTION##
###################################

########################
##START STORE FUNCTION##
########################        
def theStore():
  global programRun
  global rupeeCount
  global heroWeapon
  global potionCount
  global spellCount
  printNow("Welcome to the armory of Glossimer Meadows.")
  raw_input()
  printNow("We have a variety of weapons, potions and spells.")
  raw_input()
  storeOpen = true
  while storeOpen == true:
    printNow("You currently have " + str(rupeeCount) + " rupees.\n" +
             "You current weapon is " + str(heroWeapon) + ".\n" + 
             "Current potion count = " + str(potionCount) + ".\n" +
             "Current spell count = " + str(spellCount) + ".\n")
    storeChoice = requestString("What would you like to purchase: \n" +
                                "(1) Weapon \n" +
                                "(2) Potion \n" +
                                "(3) Spell \n" +
                                "(4) Exit store and continue on quest\n" + 
                                "(5) Quit")
    if storeChoice == '1':
      weaponPurchase()
      storeOpen = true
    if storeChoice == '2':
      potionPurchase()
      storeOpen = true
    if storeChoice == '3':
      spellPurchase()
      storeOpen = true
    if storeChoice == '4':
      printNow("Thank you. Good luck on your quest.\n" +
               "Please use this secret hatch door and ladder to go down to the Foyer on B-1")
      raw_input()
      programRun = true
      storeOpen = false
    if storeChoice == '5':
      printNow("Are you scared?")
      raw_input()
      programRun = false
      storeOpen = false
  if programRun == true:
    foyer()
  else:
    programRun = false
######################
##END STORE FUNCTION##
######################

##################################
##START WEAPON PURCHASE FUNCTION##
##################################
def weaponPurchase():
  global heroWeapon
  global weaponAttack
  global rupeeCount
  weaponOpen = true
  while weaponOpen == true:
    weaponChoice = requestString("Which weapon do you wish to wield:\n" +
                                 "(1) Dagger = 500 rupees\n" +
                                 "(2) Short Sword = 1000 rupees\n" +
                                 "(3) Battle Ax = 1500 rupees\n" + 
                                 "(4) Long Sword = 2000 rupees\n" +
                                 "(5) Exit weapon purchase.\n" +
                                 "(6) Quit")
    if (weaponChoice == '1'):
      if rupeeCount < 500:
        printNow("You do not have enough rupees.")
        raw_input()
      elif heroWeapon == 'None':
        printNow("You now wield the 'Dagger of Courage,' which inflicts damage between 5-50.")
        heroWeapon = 'Dagger'
        rupeeCount = rupeeCount - 500
        raw_input()
      elif heroWeapon == 'Dagger':
        printNow("You already own the 'Dagger of Courage!'")
        raw_input()
      else:
        printNow("You currently wield the '" + heroWeapon + ".'")
        weaponDecision = requestString("Are you sure you want to proceed? (y/n)")
        if weaponDecision == 'y':
          printNow("You now wield the 'Dagger of Courage,' which inflicts damage between 5-50.")
          heroWeapon = 'Dagger'
          rupeeCount = rupeeCount - 500
          raw_input()
        else:
          weaponPurchase()
          
    if weaponChoice == '2':
      if rupeeCount < 1000:
        printNow("You do not have enough rupees.")
        raw_input()
      elif heroWeapon == 'None':
        printNow("You now wield the 'Short Sword of Agility,' which deals a swift strike ranging between 50-100.")
        heroWeapon = 'Short Sword'
        weaponAttack = random.randint(50, 100)
        rupeeCount = rupeeCount - 1000
        raw_input()
      elif heroWeapon == 'Short Sword':
        printNow("You already own the 'Short Sword of Agility!'")
        raw_input()
      else:
        printNow("You currently wield the '" + heroWeapon + ".'")
        weaponDecision = requestString("Are you sure you want to proceed? (y/n)")
        if weaponDecision == 'y':
          printNow("You now wield the 'Short Sword of Agility,' which deals a swift strike ranging between 50-100.")
          heroWeapon = 'Dagger'
          weaponAttack = random.randint(100, 100)
          rupeeCount = rupeeCount - 1000
          raw_input()
        else:
          weaponPurchase()
          
    if weaponChoice == '3':
      if rupeeCount < 1500:
        printNow("You do not have enough rupees.")
        raw_input()
      elif heroWeapon == 'None':
        printNow("You now wield the 'Battle Ax of Fortitude,' which deals a brute force blow ranging from 100-150.")
        heroWeapon = 'Battle Ax'
        weaponAttack = random.randint(100, 150)
        rupeeCount = rupeeCount - 1500
        raw_input()
      elif heroWeapon == 'Battle Ax':
        printNow("You already own the 'Battle Ax of Fortitude!'")
        raw_input()
      else:
        printNow("You currently wield the '" + heroWeapon + ".'")
        weaponDecision = requestString("Are you sure you want to proceed? (y/n)")
        if weaponDecision == 'y':
          printNow("You now wield the 'Battle Ax of Fortitude,' which deals a brute force blow ranging from 100-150.")
          heroWeapon = 'Battle Ax'
          weaponAttack = random.randint(100, 150)
          rupeeCount = rupeeCount - 1500
          raw_input()
        else:
          weaponPurchase()
        
    if weaponChoice == '4':
      if rupeeCount < 2000:
        printNow("You do not have enough rupees.")
        raw_input()
      elif heroWeapon == 'None':
        printNow("You now wield the 'Long Sword of Might,' which punishes the enemy with a force ranging between 150-200.")
        heroWeapon = 'Long Sword'
        weaponAttack = random.randint(150, 200)
        rupeeCount = rupeeCount - 2000
        raw_input()
      elif heroWeapon == 'Long Sword':
        printNow("You already own the 'Long Sword of Might!'")
        raw_input()
      else:
        printNow("You currently wield the '" + heroWeapon + ".'")
        weaponDecision = requestString("Are you sure you want to proceed? (y/n)")
        if weaponDecision == 'y':
          printNow("You now wield the 'Long Sword of Might,' which punishes the enemy with a force ranging between 150-200.")
          heroWeapon = 'Long Sword'
          weaponAttack = random.randint(150, 200)
          rupeeCount = rupeeCount - 2000
          raw_input()
        else:
          weaponPurchase()
    if weaponChoice == '5':
      storeOpen = true
      weaponOpen = false
    if weaponChoice == '6':
      weaponOpen = false
################################
##END WEAPON PURCHASE FUNCTION##
################################

##################################
##START POTION PURCHASE FUNCTION##
##################################
def potionPurchase():
  global potionCount
  global rupeeCount
  potionChoice = requestString("Potions allow you to heal yourself by 25-75 health during battle.\n" +
                               "Potions can be purchased for 200 rupees.\n" +
                               "How many potions would you like to buy?")                       
  numPotionBought = int(potionChoice)
  if rupeeCount < (numPotionBought * 200):
    printNow("You do not have enough rupees.")
    raw_input()
  else:
    printNow("Thank you for purchasing " + potionChoice + " potion(s)!")
    potionCount = potionCount + numPotionBought
    rupeeCount = rupeeCount - (numPotionBought * 200)
    raw_input()
################################
##END POTION PURCHASE FUNCTION##
################################

#################################
##START SPELL PURCHASE FUNCTION##
#################################
def spellPurchase():
  global spellCount
  global rupeeCount
  spellChoice = requestString("A spell casted on the enemy will inflict damage to the enemy ranging from 50-150.\n" +
                              "Spells can be purchased for 100 rupees?\n" +
                              "How many spells would you like to buy?")
  numSpellBought = int(spellChoice)
  if rupeeCount < (numSpellBought * 100):
    printNow("You do not have enough rupees.")
    raw_input()
  else:
    printNow("Thank you for purchasing " + spellChoice + " spell(s)!")
    spellCount = spellCount + numSpellBought
    rupeeCount = rupeeCount - (numSpellBought * 100)
    raw_input()
###############################
##END SPELL PURCHASE FUNCTION##
###############################

#################################
##START FIGHT SEQUENCE FUNCTION##
#################################
def fightSequence(enemyHealth, healthGain, rupeeTreasure):
  global defaultHeroHealth
  global defaultHeroAttack
  global weaponAttack
  global potionCount
  global spellCount
  global potionHeal
  global spellAttack
  
  attackCommand = true
  heroHealth = defaultHeroHealth
 
  while (enemyHealth > 0) or (defaultHeroHealth > 0):
    #while attackCommand == true:
      heroCommand = requestString("Attack (a), use potion (p), use spell (s), or flee (f)?")

      if heroCommand == 'a':
        heroAttack = defaultHeroAttack + weaponAttackValue()    
        strHeroAttack = str(heroAttack)
        printNow("You just attacked Mini Boss, dealing " + strHeroAttack + " damage.")
        enemyAttack = enemyAttackValue()
        strEnemyAttack = str(enemyAttack)
        printNow("Mini Boss retaliated, dealing " + strEnemyAttack + " damage.")
        defaultHeroHealth = defaultHeroHealth - enemyAttack
        enemyHealth = enemyHealth - heroAttack
        raw_input()

      if heroCommand == 'p':
        potionCount
        if potionCount > 0:
          potionHeal
          printNow("You used a potion and regained " + potionHeal + " health.")
          potionCount = potionCount - 1
          enemyChanceAttack = random.randint(0, 1)
          if enemyChanceAttack == 1:
            enemyAttack = enemyAttackValue
            printNow("Mini Boss just attacked you, dealing" + enemyAttack + " damage.")
          else:
            printNow("Mini Boss attempted to attack you, but failed")
        else:
          printNow("Sorry, you are all out of potions.")
          potionHeal = 0
          enemyAttack = 0
        attackCommand = true
        heroHealth = heroHealth + potionHeal - enemyAttack
            
      if heroCommand == 's':
        spellCount
        if spellCount > 0:
          spellAttack
          printNow("You used a spell, dealing " + spellAttack + " damage.")
          spellCount = spellCount - 1
          enemyAttack = enemyAttackValue
          printNow("Mini Boss retaliated, dealing " + enemyAttack + " damage.")
        else:
          printNow("Sorry, you are all out of spells.")
          spellAttack = 0
          enemyAttack = 0
        attackCommand = true
        enemyHealth = enemyHealth - spellAttack
        heroHealth = heroHealth - enemyAttack

      if heroCommand == 'f':
        printNow("You have fled from the battle!")
        attackCommand = false

  if heroHealth == 0:
    printNow("You have been defeated!")
    commandMove = 'exit'
    fightOutcome = 'loss'
  if enemyHealth == 0:
    printNow("You have defeated the Mini Boss! You gained " + healthGain + " health. Your attack has increased by " + attackGain + ". Your winnings include " + rupeeTreasure + " rupees and 1 out of the 4 pieces of the 'Key to Freedom!'")
    defaultHeroHealth = defaultHeroHealth + healthGain
    defaultHeroAttack = defaultHeroAttack + attackGain
    rupeeCount = rupeeCount + rupeeTreasure
    commandMove = 'exit'
    fightOutcome = 'win'
  
  return(heroHealth, potionCount, spellCount, commandMove, rupeeCount, fightOutcome)
###############################
##END FIGHT SEQUENCE FUNCTION##
###############################

########################
##START FOYER FUNCTION##
########################
def foyer():
  global keyToFreedom
  global keyPieceCollected1
  global keyPieceCollected2
  global keyPieceCollected3
  global keyPieceCollected4

  foyerOpen = true
  if keyToFreedom < 4:
    printNow("You are currently in the foyer of B-1... an empty square white room.\n" +
             "Four black doors surround you, one in each corner.\n" +
             "In the southwest corner, the door reads 'Room 1.'\n" +
             "In the northwest corner, the door reads 'Room 2.'\n" +
             "In the northeast corner, the door reads 'Room 3.'\n" +
             "And in the southeast corner, the door reads 'Room 4.'")
    raw_input()
    while foyerOpen == true:
      foyerChoice = requestString("Which room shall you choose?\n" +
                                  "(1) Room 1\n" +
                                  "(2) Room 2\n" + 
                                  "(3) Room 3\n" +
                                  "(4) Room 4\n" +
                                  "(5) Go back to Store\n" +
                                  "(6) Quit")
      if foyerChoice == '1':
        if keyPieceCollected1 == false:
          room1()
        if keyPieceCollected1 == true:
          printNow("You have already gone through this room.")
          raw_input()
      if foyerChoice == '2':
        if keyPieceCollected2 == false:
          room2()
        if keyPieceCollected2 == true:
          printNow("You have already gone through this room.")
          raw_input()
      if foyerChoice == '3':
        if keyPieceCollected3 == false:
          room3()
        if keyPieceCollected3 == true:
          printNow("You have already gone through this room.")
          raw_input()
      if foyerChoice == '4':
        if keyPieceCollected4 == false:
          room4()
        if keyPieceCollected4 == true:
          printNow("You have already gone through this room.")
          raw_input()
      if foyerChoice == '5':
        theStore()
      if foyerChoice == '6':
        printNow("Run away scared!")
        raw_input()
        foyerOpen = false
      
  else:
    printNow("You have defeated all 4 Mini Bosses and obtained the 4 pieces that make the 'Key to Freedom!'\n" +
             "A secret door is revealed in the middle of the foyer.")
    raw_input()
    foyerKeyChoice = requestString("What would you like to do?\n" +
                                "(1) Use the 'Key to Freedom' to continue through the secret door\n" +
                                "(2) Go back to store?\n" +
                                "(3) Quit")
    if foyerKeyChoice == '1':
      finalFight()
    elif foyerKeyChoice == '2':
      theStore()
    else:
      programRun = false
######################
##END FOYER FUNCTION##
######################

#########################
##START ROOM 1 FUNCTION##
#########################
def room1():
  global keyPiece1
  global keyPieceCollected1
  global enemyNumber
  global enemyHealth1
  enemyNumber = '1'
  
  #room1Open = true
  printNow("You have entered into Room 1.\n" +
           "In the middle of the room you see a pile of rupees and a piece of a key.")
  raw_input()
  commandMove = requestString("Where would you like to move:\n" +
                              "'forward'\n" +
                              "Take the door to the 'left'\n" +
                              "Take the door to the 'right'\n" +
                              "'Exit' back into the foyer\n" +
                              "'Quit'")
  if commandMove == 'forward':
    printNow("Mini Boss has emerged from the shadows and has engaged you for battle. Prepare to fight!")
    healthGain = 100
    attackGain = 25
    rupeeTreasure = 1000
    enemyHealth = enemyHealth1
    raw_input()
    fightSequence(enemyHealth, healthGain, rupeeTreasure)
    if fightOutcome == 'win':
      keyPiece1 = 1
      keyPieceCollected1 = true
  if commandMove == 'left':
    room4()
  if commandMove == 'right':
    room2()
  if commandMove == 'exit':
    foyer()
  if commandMove == 'quit':
    programRun = false
#######################
##END ROOM 1 FUNCTION##
#######################

#########################
##START ROOM 2 FUNCTION##
#########################
def room2():
  printNow("You have entered into Room 2. In the middle of the room you see a pile of rupees and a piece of a key.")
  commandMove = requestString("What would you like to do: move 'forward,' take the door to the 'left,' take the door to the 'right,' 'exit' back into the foyer, or 'quit' the game?")
  if commandMove == 'forward':
    printNow("Mini Boss has emerged from the shadows and has engaged you for battle. Prepare to fight!")
    enemyHealth = 1500
    enemyAttackValue = random.randint(50, 150)
    healthGain = 250
    attackGain = 50
    rupeeTreasure = 1500
    fightSequence(enemyHealth, enemyAttackValue, healthGain, rupeeTreasure)
    if fightOutcome == 'win':
      keyPiece2 = 1
      keyPieceCollected2 = true
  if commandMove == 'left':
    room1()
  if commandMove == 'right':
    room3()
  if commandMove == 'exit':
    foyer()
  if commandMove == 'quit':
    programRun = false
  return(defaultHeroHealth, defaultHeroAttack, potionCount, spellCount, rupeeCount, keyPiece2, keyPieceCollected2, programRun)
#######################
##END ROOM 2 FUNCTION##
#######################

#########################
##START ROOM 3 FUNCTION##
#########################
def room3():
  printNow("You have entered into Room 3. In the middle of the room you see a pile of rupees and a piece of a key.")
  commandMove = requestString("What would you like to do: move 'forward,' take the door to the 'left,' take the door to the 'right,' 'exit' back into the foyer, or 'quit' the game?")
  if commandMove == 'forward':
    printNow("Mini Boss has emerged from the shadows and has engaged you for battle. Prepare to fight!")
    enemyHealth = 2000
    enemyAttackValue = random.randint(150, 200)
    healthGain = 500
    attackGain = 75
    rupeeTreasure = 2000
    fightSequence(enemyHealth, enemyAttackValue, healthGain, rupeeTreasure)
    if fightOutcome == 'win':
      keyPiece3 = 1
      keyPieceCollected3 = true
  if commandMove == 'left':
    room2()
  if commandMove == 'right':
    room4()
  if commandMove == 'exit':
    foyer()
  if commandMove == 'quit':
    programRun = false
  return(defaultHeroHealth, defaultHeroAttack, potionCount, spellCount, rupeeCount, keyPiece3, keyPieceCollected3, programRun)
#######################
##END ROOM 3 FUNCTION##
#######################

#########################
##START ROOM 4 FUNCTION##
#########################
def room4():
  printNow("You have entered into Room 3. In the middle of the room you see a pile of rupees and a piece of a key.")
  commandMove = requestString("What would you like to do: move 'forward,' take the door to the 'left,' take the door to the 'right,' 'exit' back into the foyer, or 'quit' the game?")
  if commandMove == 'forward':
    printNow("Mini Boss has emerged from the shadows and has engaged you for battle. Prepare to fight!")
    enemyHealth = 2500
    enemyAttackValue = random.randint(200, 250)
    healthGain = 750
    attackGain = 100
    rupeeTreasure = 2500
    fightSequence(enemyHealth, enemyAttackValue, healthGain, rupeeTreasure)
    if fightOutcome == 'win':
      keyPiece4 = 1
      keyPieceCollected4 = true
  if commandMove == 'left':
    room3()
  if commandMove == 'right':
    room1()
  if commandMove == 'exit':
    foyer()
  if commandMove == 'quit':
    programRun = false
  return(defaultHeroHealth, defaultHeroAttack, potionCount, spellCount, rupeeCount, keyPiece4, keyPieceCollected4, programRun)
#######################
##END ROOM 4 FUNCTION##
#######################

###########################################
##START EPIC BOSS FIGHT SEQUENCE FUNCTION##
###########################################
def epicBossFightSequence(epicBossHealth, epicBossAttackValue):
  attackCommand = true
  heroHealth = defaultHeroHealth
    
  while (epicBossHealth > 0) or (heroHealth > 0):
    while attackCommand == true:
      heroCommand = requestString("Attack (a), use potion (p), use spell (s), or flee (f)?")
        
      if heroCommand == 'a':
        heroAttack = defaultHeroAttack + weaponAttack
        printNow("You just attacked Dark Lord Bob, dealing " + heroAttack + " damage.")
        epicBossAttackChoice = random.randint(0, 1)
        if epicBossAttackChoice == 1:
          epicBossAttack = epicBossAttackValue
          printNow("Dark Lord Bob retaliated, dealing " + epicBossAttack + " damage.")
        else:
          epicBossAttack = epicBossSpellValue
          printNow("Dark Lord Bob casted a spell dealing " + epicBossAttack + " damage.")
        attackCommand = true
        epicBossHealth = epicBossHealth - heroAttack
        heroHealth = heroHealth - epicBossAttack
        
      if heroCommand == 'p':
        potionCount
        if potionCount > 0:
          potionHeal
          printNow("You used a potion and regained " + potionHeal + " health.")
          potionCount = potionCount - 1
          epicBossChanceAttack = random.randint(0, 1)
          if epicBossChanceAttack == 1:
            epicBossAttackChoice = random.randint(0, 1)
            if epicBossAttackChoice == 1:
              epicBossAttack = epicBossAttackValue
              printNow("Dark Lord Bob retaliated, dealing " + epicBossAttack + " damage.")
            else:
              epicBossAttack = epicBossSpellValue
              printNow("Dark Lord Bob casted a spell dealing " + epicBossAttack + " damage.")
          else:
            printNow("Dark Lord Bob attempted to attack you, but failed")
        else:
          printNow("Sorry, you are all out of potions.")
          potionHeal = 0
          enemyAttack = 0
        attackCommand = true
        heroHealth = heroHealth + potionHeal - epicBossAttack
      
      if heroCommand == 's':
        spellCount
        if spellCount > 0:
          spellAttack
          printNow("You used a spell, dealing " + spellAttack + " damage.")
          spellCount = spellCount - 1
          epicBossAttackChoice = random.randint(0, 1)
          if epicBossAttackChoice == 1:
            epicBossAttack = epicBossAttackValue
            printNow("Dark Lord Bob retaliated, dealing " + epicBossAttack + " damage.")
          else:
            epicBossAttack = epicBossSpellValue
            printNow("Dark Lord Bob casted a spell dealing " + epicBossAttack + " damage.")
        else:
          printNow("Sorry, you are all out of spells.")
          spellAttack = 0
          enemyAttack = 0
        attackCommand = true
        epicBossHealth = epicBossHealth - spellAttack
        heroHealth = heroHealth - epicBossAttack
            
      if heroCommand == 'f':
        printNow("You have fled from the battle!")
        attackCommand = false
        potionCount
        spellCount
  if heroHealth == 0:
    printNow("You have been defeated!")
    commandMove = 'exit'
    fightOutcome = 'loss'
  if epicBossHealth == 0:
    printNow("You have defeated Dark Lord Bob!")
    printNow("Dark Lord Bob: 'What?!... Huh?!...'")
    printNow("Dark Lord Bob: '...No, it can't be possible?!...'")
    printNow("Dark Lord Bob: '...How did a puny person like you defeat me... the great Dark Lord Bob?!'")
    printNow("Epic Hero: 'You heavily underestimated me Dark Lord Bob!'")
    printNow("Epic Hero: 'I am not a puny person...'")
    printNow("Epic Hero: '... I... AM... EPIC HERO!!!'")
    printNow("Thank you for playing the Epic Strategy Game!")
    commandMove = 'quit'
        
  return(heroHealth, potionCount, spellCount, commandMove, rupeeCount, fightOutcome)
#########################################
##END EPIC BOSS FIGHT SEQUENCE FUNCTION##
#########################################

##############################
##START FINAL FIGHT FUNCTION##
##############################
def finalFight():
  printNow("You have entered the chambers of Dark Lord Bob.")
  printNow("Dark Lord Bob: 'Epic Hero?! HAHAHA! More like PUNY HERO! PREPARE TO DIE!'")
  printNow("Watch out! Dark Lord Bob has engaged in battle with you.")
  epicBossHealth = 5000
  epicBossAttackValue = random.randint(200, 400)
  epicBossSpellValue = random.randint(150, 300)
  fightSequence(epicBossHealth, epicBossAttackValue, epicBossSpellValue)
  if commandMove == 'exit':
    foyer()
  if commandMove == 'quit':
    programRun = false
############################
##END FINAL FIGHT FUNCTION##
############################





















