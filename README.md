# Marvel-Snap-Ultra-Robust-3-day-coding

This Marvel Snap auto bot ultra robust for your Season Pass and daily mission. 
It/He/She does not have inteligence by design but be put some sort of inteligence from algorithm.

Ultra Robust:
Handle any situation:
The script/program designed to last turn 19 for Kong, instead i forget the infinite Kong loop be fixed.
It designed to fix any turns game up to infinity, even in its brian doesn't have conclusion about what is button about beyond turn 6 or turn 5/7, 6/7 to 7/7.

You can simple cover the screen in the mid of game, doing something, by short period let's say 10 seconds it will still catch up and doing the job.
You leave any situation that this program can not figuring out such as cover the screen too long, it will recontinue at any given siuation but not designed to be shown except in the game match, or the mian page as not given any ideads about what outside main page: News look like to go back to mian page.
Example: 
Counter infinite Kong, turn 7 games.
leaving any situation and returning to game: usually when the match is finished leave the collect rewards button.
Meet any error such as: Reconnect to the game, be shown a new card, clicked a card and showing the card detail in the game all handled by algorithm.

It doesn't has brain or he/she, but has inteligence be given by me.

Quick start:
```python
red_button_array, play_button_array,collect_button_array,next_button_array,retreat_button_array,turn1next_button_array, turn2next_button_array, turn3next_button_array, turn4next_button_array, turn5next_button_array, Endnext_button_array = Load_buttons('C:/Users/acer/Pictures/Snap/Snap button')
image_list = Read_deck("C:/Users/acer/Pictures/Snap/Discard deck/Cards")
```
In the script changing the path to read your card image path: Folder.
You can simply download my Snap button folder images for button recongnition.

I'm running a Agantha liked deck but much more flexible.

For custmise deck:
Crop your in-match card image like i showned in the card image folder for better recongnition: It's not a fancy techknowledge but simple template match at balance.
Put your deck-card image in the folder and put path: Read_deck("C:/Users/acer/Pictures/Snap/Discard deck/Cards")
Build your turn-card recongnition list
```python
Turn1_card_tupo = (1,['Sunspot', 'Blade'])
Turn2_card_tupo = (2,['Sunspot','Blade','Wolverine'])
Turn3_card_tupo = (3,['Lady','Sunspot','Blade','Wolverine'])
Turn4_card_tupo = (4,['Jubilee','Dracula','Ghost','Sunspot','Blade','Wolverine'])
Turn5_card_tupo = (5,['Spider Woman','Jubilee','Dracula','Ghost Rider','Sunspot','Blade','Wolverine'])
Turn6_card_tupo = (6,['Hela','Hulk','AmericaChavez','Spider Woman','Jubilee','Dracula','Ghost Rider','Sunspot','Blade','Wolverine'])
```
By for loop favor and algorithm, it/he/she will loop thought all the first card name in the given image recongnition folder. So 'Hela' at turn 6 if favorable will be the first put out.

Don't worry beyond turn 6, it built to last forever at one match and recongnize any time the match is over or anything happend inside the match. (Currently are only errors like elements)

You can free use my deck:
![11](https://user-images.githubusercontent.com/124453554/233508648-852f3538-26df-498b-93a2-53c2c76fe046.png)
Some tips:
maybe 2 hours one Season Pass level. It's slow but very fast for completing daily mission for running 10 games straight.



Some testing/Experience:
For robust level, at one disconnect game at main menu, it designed to recongize the event happened and quickly clicked the reconnect button to reconnect the game. But i requit the game when connecting, shut the program, mainly connect the game, even by algorithm it doesn't given to handle situation like that, but by algorithm design it still finish the game and started new games.

Some best results:

![ScreenPerformance1 (2)](https://user-images.githubusercontent.com/124453554/233507994-f2f9d38d-8c6b-4f9c-bbb1-11a84877da32.png)
![ScreenWin](https://user-images.githubusercontent.com/124453554/233508163-e9b55083-24f3-4da2-8afc-8e1796adb811.png)


Some ironic results:


A robusted AI bot with poor vision: like a strong old man.
But it will be defintely robusted handle any situations, repeat games, clear missions, win lanes and even win some games.



