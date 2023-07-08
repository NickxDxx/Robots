# Marvel-Snap Auto Life

-------------
WARNING: Only for jobs and self-interest thats why uploaded. Do not harm game in meaningless way.
-------------


7 minutes game play: YouTube https://www.youtube.com/watch?v=1NvyePpsOCw

Extreme testing, Starting program at the end of game. 
https://youtube.com/shorts/3hrlQzItkQw?feature=share

Extreme testing, Starting program at needing recognize state, finding its state and finishing game with brand new next game recontinue circle. 
https://youtu.be/VjReNp9dM0g


Current win rate in 600 games: 21%

Preset can be download and have rooms for you to cusmise:
A preset Discard deck image folder and preset Deck order
Defualt can be download deck infomation:

![11](https://user-images.githubusercontent.com/124453554/233508648-852f3538-26df-498b-93a2-53c2c76fe046.png)

Quick start
1. Read the button images
   Download the button image folder and set the root on script.
   Dwonload the deck images, set or your own deck images like what i used in the deck image folder. 
   
```python
red_button_array, play_button_array,collect_button_array,next_button_array,retreat_button_array,turn1next_button_array, turn2next_button_array, turn3next_button_array, turn4next_button_array, turn5next_button_array, Endnext_button_array = Load_buttons('C:/Users/acer/Pictures/Snap/Snap button')
image_list = Read_deck("C:/Users/acer/Pictures/Snap/Discard deck/Cards")
```
Custumise your deck: By for loop favor Jane with pick the the card by left to right order if cards appeared (Or be detected!!!) in your hand.
Always good thing to think what is the priority in your deck. As i said it design to play up to infinity, from turn 6 it will always check the cards in turn 6 order and play them.

```python
Turn1_card_tupo = (1,['Sunspot', 'Blade'])
Turn2_card_tupo = (2,['Sunspot','Blade','Wolverine'])
Turn3_card_tupo = (3,['Lady','Sunspot','Blade','Wolverine'])
Turn4_card_tupo = (4,['Jubilee','Dracula','Ghost','Sunspot','Blade','Wolverine'])
Turn5_card_tupo = (5,['Spider Woman','Jubilee','Dracula','Ghost Rider','Sunspot','Blade','Wolverine'])
Turn6_card_tupo = (6,['Hela','Hulk','AmericaChavez','Spider Woman','Jubilee','Dracula','Ghost Rider','Sunspot','Blade','Wolverine'])
```


maybe 2 hours one Season Pass level. It's slow but very fast for completing daily mission for running 10 games straight.



Some testing/Experience:
For robust level, at one disconnect game at main menu, it designed to recongize the event happened and quickly clicked the reconnect button to reconnect the game. But i requit the game when connecting, shut the program, mainly connect the game, even by algorithm it doesn't given to handle situation like that, but by algorithm design it still finish the game and started new games.

Some best results:

![ScreenPerformance1 (2)](https://user-images.githubusercontent.com/124453554/233507994-f2f9d38d-8c6b-4f9c-bbb1-11a84877da32.png)
![ScreenWin](https://user-images.githubusercontent.com/124453554/233508163-e9b55083-24f3-4da2-8afc-8e1796adb811.png)


Some ironic results:
![Screenshot Ironic (2)](https://user-images.githubusercontent.com/124453554/233509896-7d970d4f-2c72-43a4-817b-7fab626751db.png)


A robusted AI bot with poor vision: like a strong old man.
But it will be defintely robusted handle any situations, repeat games, clear missions, win lanes and even win some games.



