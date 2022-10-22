
TTVDROPBOT自動重啟按鍵精靈腳本<br>
<br>
用於https://github.com/Zaarrg/TTVDropBot 2.0.0.4版<br>
2.0.0.4版會出ERROR<br>
因此會TTVDropBot會停掉<br>
<br>
因此需要自動重啟腳本來定時自動重啟TTVDROPBOT<br>
<br>
配合WINDOWS TERMINAL<br>
先做一個TTVDROPBOT的設定檔，並在設定->啟動->預設設定檔選擇這個TTVDROPBOT的設定檔<br>
https://i.imgur.com/fLct2H3.png<br>
到各個裝了的CONFIG的目錄右鍵->啟動終端機<br>
<br>
之於製作這些CONFIG則是你事先在TTVDROPBOT了登入1次帳號<br>
把CONFIG檔案複製出來到其他目錄<br>
然後更改twitch-session.json內的AUTH-TOKEN<br>
這樣就能完成所有帳號的CONFIG<br>
<br>
這樣就可以掛N個帳號了<br>
每次再用按鍵精靈腳本啟動(單次啟動腳本)<br>
用人手啟動太慢太笨了<br>
如果人離開又打算掛機，則使用自動重啟腳本對應2.0.0.4的ERROR BUG<br>
需要使用電腦時則使用單次啟動腳本就好<br>
<br><br><br>
===========================================================================
2022/10/18更新<br>
加入FIREFOX腳本<br>
FIREFOX安裝兩個插件<br>
https://addons.mozilla.org/zh-TW/firefox/addon/twitchautoclicker/ <br>
https://addons.mozilla.org/zh-TW/firefox/addon/multi-account-containers/ <br>
預先新增容器及登入TWITCH帳號<br>
就可以使用
===========================================================================
2022/10/22更新<br>
優化腳本最後的計時<br>
應該不用自己算時間<br>
