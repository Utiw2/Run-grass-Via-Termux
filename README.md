# Run-grass-Via-Termux

-Install gitbash-

pkg update && pkg upgrade

pkg install git

termux-setup-storage (izinkan)


pkg instal gh

gh auth login 

1.select github.com
2.https
3.auth token
Paste token(get token on github👇)

-login github-

1.developer setting
2.Personal ascces token
3.Token clasic
4.Generate token
5.Beta 
5.add name
6.scrol down generate token
6.Copas token paste to termux


-Install python-

pkg upgrade

pkg install python
Atau
pkg install python2

Lanjut 
cd storage

git clone https://github.com/im-hanzou/getgrass.git

cd getgrass

pip install -r requirements.txt

-Edit file proxy-

1.nano proxy_list.txt 

Copas proxy 
save

https://pst.innomi.net/paste/tucxgvtupm3mvdquruaevzrvt7bgpuvx (tmpek)

ctrl x 
Y
Enter

python run.py
paste user id grass
