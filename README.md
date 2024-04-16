# m11_docker
studing the basics and doing the exercice
## Instaling ubuntu
with the oficial manual https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox&ved=2ahUKEwjoxeG7qMaFAxXTa0EAHZQTApUQFnoECAYQAQ&usg=AOvVaw0mT_gnhKfHAIYViolDpX7Z

- error1: cant open the terminal becase is not configuret as United States
https://askubuntu.com/questions/1435918/terminal-not-opening-on-ubuntu-22-04-on-virtual-box-7-0-0
- error2: the name of the host need be zara

### Add user for docker
Instaación mediandte curl redirreción a bash
```bash
$ curl https://get.docker.com | sudo bash
```
Usuario para poder tener acceso
```bash
$ sudo usermod -aG docker your-user
```
Una vez que lo tengamos reiniciamos la máquina
```bash
$ sudo usermod -aG docker your-user
```
## Run the docker
Run the docker
```bash
docker run hello-world
```
Show registred comands
```bash
$ docker ps -a
```
Show images thata we have in the docker
```bash
$ docker images
```
