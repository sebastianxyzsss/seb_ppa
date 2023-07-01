## to add ppa

```
curl -s --compressed "https://sebastianxyzsss.github.io/seb_ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/seb_ppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/seb_list_file.list "https://sebastianxyzsss.github.io/seb_ppa/seb_list_file.list"
sudo apt update
```

## then to install

```
sudo apt install tg
```
