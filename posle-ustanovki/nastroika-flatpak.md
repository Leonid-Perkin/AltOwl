# Настройка Flatpak

Flatpak — это система упаковки и распространения приложений, позволяющая запускать программы в изолированной среде на разных дистрибутивах Linux.

### Установка с помощью epm play

{% hint style="info" %}
При установке через epm сразу установится flathub, а так же применится исправление для исправления ошибки: «enabling unprivileged user namespaces»
{% endhint %}

```bash
su -
epm play flatpak
```
