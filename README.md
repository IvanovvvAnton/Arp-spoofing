# Arp-spoofing
Для начала хочется немного рассказать про наш проект, для чего он и тд
# Install pnet lab
Описание установки pnet lab
First of all :nerd_face:
https://pnetlab.com/pages/main
For example:  
```
console_2nd: 
  type: list # type of configuration (list, number, text, checkbox)
  value: ''  # the default value
  options:   # Options in case type is list
    '': 'Empty'
    telnet: Telnet
    rdp: RDP
    vnc: VNC
    ssh: SSH
    http: HTTP
    https: HTTPS
  wipe: 1 # 1 means this field needs to be wiped to get affected
  width: 6 # width of the input box 6/12 screen width
```
# Как установить PnetLab и добавить функцию ishare
    Для начала необходимо перейти на официальный сайт во вкладку Download (https://pnetlab.com/pages/download) и загрузить файл с расширение .ova, далее с помощью виртуальных платформ (VMWare, VirtualBox и др.) загрузить данный файл на платформу. В данном проекте была использована виртуальная платформа VMWare. 
    Более подробный процесс установки можно также найти на официальной сайте (https://pnetlab.com/pages/documentation?slug=install-PNETlab). 
