# ubuntu-swapfile

A small and lazy utility to create a 2G swapfile on Ubuntu (server/desktop)

## dependencies :

*  curl

## usage :

```bash
sudo curl -sSf https://raw.githubusercontent.com/HailHide/ubuntu-swapfile/main/swap.sh | bash
```

## check result :

Use **htop** system monitoring utility (included in script) to check swap in mem. tab you should see a 2G swap.

```bash
htop
```