# Dev Setup

Bu repo, geliştirme ortamım için kullandığım ayarları (VS Code extensions, keybindings, vb.) içerir.

## VS Code Extensions Kurulumu

Repo içerisindeki `extensions.txt` dosyasındaki tüm eklentileri yüklemek için aşağıdaki komutu çalıştırabilirsin:

```bash
while read line; do code --install-extension "$line";done <extensions.txt

## Vs Code Extensions Listesi

Vs Code içerisindeki kurulu extensionları liste şeklinde bir dosyada toplar

```bash
code --list-extensions > extensions.list
