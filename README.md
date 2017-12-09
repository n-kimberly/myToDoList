# **Kimberly's To Do List Skill**

## This Alexa sample skill allows users to create, listen to, and update their to do list. Currently (12/08/17), the skill does not persist the list to a database. The list comes pre-populated with "stand", "sit", and "lie down" to do list items. Feel free to remove those by asking the skill to take you to the update menu.

<h1 style="text-align: center;"> Example </h1>

> Alexa, open kimberly's to do list.

      Welcome to kimberly's to do list. Do you want to create an item, view all items, or update items on kimberly's to do list?

> I would like to add to my to do list.

      Okay, what would you like to add?

> Remind me to go grocery shopping.

      GO GROCERY SHOPPING has been added! You now have 4 items. What else would you like to add? Say menu to return to the main menu.

> I would like to view my to do list.

      Sure thing!  Item 1 on your to do list is STAND, Item 2 on your to do list is SIT, Item 3 on your to do list is LIE DOWN, Item 4 on your to do list is GO GROCERY SHOPPING

> I would like to update my to do list.

      Okay, I will remind you of your to do items one by one. After each, please respond with completed, remove, or next to hear the next item. Your first item is STAND.

> Completed.

       Item removed. Your next to do item is SIT.

> Next.

      You'll need to complete that at some point in your life. Your next item is LIE DOWN.

> Remove.

      Item removed. Your next to do item is GO GROCERY SHOPPING.

> Main Menu.

      Main menu. Do you want to create an item, view all items, or update items on kimberly's to do list?

<h1 style="text-align: center;"> Skill Details </h1>

#### QuestionIntent sample utterances:

> 'What might a user say to invoke this intent?'

      Practice {language}

      Test my {language}

#### language slot values:

      python

      ruby

#### AnswerIntent sample utterances:

> 'What will Alexa say to ask the user to fill this slot?'

      Is it {answer}

      I think it's {answer}

#### answer slot values:

      length

      len

      print

      puts

      yes

      no
