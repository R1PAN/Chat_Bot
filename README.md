# All_Linux
```
apt install wget -y
wget -q https://github.com/R1PAN/Chat_Bot/raw/master/chat.x
chmod +x chat.x
mv chat.x chat
bash_path=$(command -v bash)
directory_path="${bash_path%/*}"
mv chat "$directory_path"
```
# For Termux
```
pkg install wget -y
wget -q https://github.com/R1PAN/Chat_Bot/raw/master/chat
chmod +x chat
bash_path=$(command -v bash)
directory_path="${bash_path%/*}"
mv chat "$directory_path"
```
## nb
``
Jalankan dengan mengetikan "chat"
Hapus history chat dengan mengetikan "reset"
``
