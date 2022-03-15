# ubuntu-swapfile

A small and lazy utility to create a 2G swapfile on Ubuntu (server/desktop)

## dependencies :

*  curl

```bash
sudo apt install curl
```

## usage :

```bash
sudo curl -sSf https://raw.githubusercontent.com/HailHide/ubuntu-swapfile/main/swap.sh | bash
```

note : doing this have security flaws in case of host or publishing account compromision, but is convinient.

## check result :

Use **htop** system monitoring utility (included in script) to check swap in mem. tab you should see a 2G swap.

```bash
htop
```