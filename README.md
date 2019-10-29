# NothingButSudo
Empty Sudo command that simply ignore that you have said sudo... why? Termux.

```apt update &&\
apt install wget &&\
cd /bin &&\
wget "https://raw.githubusercontent.com/MrCyjaneK/NothingButSudo/master/sudo" &&\
chmod +x sudo &&\
echo "It should work";
