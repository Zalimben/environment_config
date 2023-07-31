
## Programas

### terminator 
```shell
sudo apt-cache policy terminator
sudo apt install terminator 

```
### chromium  
```shell 
sudo apt-cache policy chromium
``` 
### git       
```shell 
sudo apt-get install git
``` 
### fzf       
```shell 
sudo apt-get install fzf
``` 
### vim       
```shell 
sudo apt-get install vim  
``` 
### htop      
```shell 
sudo apt-get install htop
``` 
### snap      
```shell 
sudo apt-get install snap
``` 
### IntelliJ  
```shell 
sudo snap install intellij-idea-ultimate --classic
``` 
### Discord   
```shell 

``` 
### Slack     
```shell 
sudo snap install slack
``` 
### FileZilla 
```shell 
sudo snap install filezilla
``` 
### Remmina   
```shell 
sudo snap install remmina
``` 
### Zoom      
```shell 
sudo snap install zoom 
``` 
### Spotify   
```shell
    curl -sS https://download.spotify.com/debian/pubkey_5E3C45D7B312C643.gpg | sudo apt-key add - 
    echo "deb http://repository.spotify.com stable non-free" | sudo tee /etc/apt/sources.list.d/spotify.list
    sudo apt-get update 
    sudo apt-get install potify-client
```

### Sublime
```shell
    wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
    echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
    sudo apt-get update
    sudo apt-get install sublime-text
```