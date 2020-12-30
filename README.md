# PocoLootFilter
## Installation
[**Filter download**](https://raw.githubusercontent.com/rockbyo5/PocoLootFilter/main/default.filter)
1. Locate your Project Diablo 2 folder. It is usually under your original Diablo 2 folder in a folder named ***ProjectD2***.
2. (Optional) If you already configured a filter, back it up now by renaming/copying your filter. Your filter name would probably be `loot.filter` or `default.filter`.
3. To install a new filter, copy the [filter](https://raw.githubusercontent.com/rockbyo5/PocoLootFilter/main/default.filter) to the `ProjectD2` folder and name it `loot.filter`. Make sure you have no `.txt` at the end of the file name. Sometime windows hides it. If you have a `.txt` at the end of the file, it can and will cause your filter not to work.
4. If you have not already, to enable the loot filter, go inside of a game and then control+click the small `settings` button in the bottom left of your screen.
5. In the new window, you need to check the box next to **Advanced item display** anbd.

![Checkboxes in settings](/images/checkboxes.png)
## Additional informations
- If items happen to have bugged out names with weird characters, the issue is most probably that your default.filter is using the wrong text encoding (You need ANSI but the default often is UTF-8). If you have this issue, i recommend doing going to the "raw file" from github using my download link and then using `ctrl+s` to save the whole file, replace the existing `default.filter`. Everyone that messaged me with this issue had used the copy-paste function to paste the text in the file.
- If you find any issues with the filter, you are welcome to either message me on discord at **ElPocoBurrito#5641** or to create a pull request on github which i will merge as soon as i have free time.

## Credits
I want to thank WolfieeifloW and Sawyer from the PD2 discord for their help understanding stuff. I also want to also thank WolfieeifloW, Bulleti (EuropeBattle.net) and Anirml for their work on their own filters which i snatched small parts of and analysed to better understand how to improve mine.
