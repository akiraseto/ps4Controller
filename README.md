# ps4Controller
ラズパイからPS4を制御する

#参考
##Git repository:ps4-waker
https://github.com/dhleong/ps4-waker

##Playstation store
https://store.playstation.com/ja-jp/home/games

#コマンド

##PS4起動
sudo ps4-waker

##トルネ起動
sudo ps4-waker start CUSA00442

##アマゾンプライム・ビデオ起動
sudo ps4-waker start CUSA03099

##PS4スタンバイ
sudo ps4-waker standby

##PS4電源off
sudo ps4-waker remote ps:1000 down down down up right down down down down up enter
