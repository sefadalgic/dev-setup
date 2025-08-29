# Dev Setup

Bu repo, geliştirme ortamım için kullandığım ayarları (VS Code extensions, keybindings, vb.) içerir.

## VS Code Extensions Kurulumu

Repo içerisindeki `extensions.txt` dosyasındaki tüm eklentileri yüklemek için aşağıdaki komutu çalıştırabilirsin:

```bash
while read line; do code --install-extension "$line";done <extensions.txt
