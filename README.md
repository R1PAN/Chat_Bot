# All_Linux
```
curl -s -o chat https://raw.githubusercontent.com/R1PAN/Chat_Bot/master/chat
chmod +x chat
bash_path=$(command -v bash)
directory_path="${bash_path%/*}"
mv chat "$directory_path"
```

# TERMUX
```
pkg install wget -y
wget -q https://github.com/R1PAN/Chat_Bot/raw/master/chat.x
chmod +x chat.x
mv chat.x chat
bash_path=$(command -v bash)
directory_path="${bash_path%/*}"
mv chat "$directory_path"
```
