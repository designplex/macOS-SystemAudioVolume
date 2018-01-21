# macOS-SystemAudioVolume
AppleScript to change volume level of the startup tone on Mac.
Macの起動音を調整するためのスクリプトです。


sudo chmod 755 で実行権限を与えます。
sudo defaults read com.apple.loginwindow で設定を確認。
sudo defaults write com.apple.loginwindow LogoutHook でMacのログアウト時に指定した音量を下げます。
