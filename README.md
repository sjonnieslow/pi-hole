# pi-hole
Toevoegen aan lijst is koppelen van deze URL:
```
https://raw.githubusercontent.com/sjonnieslow/pi-hole/refs/heads/master/block-list.txt
```


# Updaten
Inloggen via ssh gebruiker@192...

Updaten van Linux inclusief pi-hole
```
sudo apt update
sudo apt full-upgrade

```
eventueel
```
sudo reboot
```

Updaten van pi-hole zelf
```
pihole -v
```
daarna
```
pihole -up
```


