# SuOS pakketrepository

Pacman-repository voor SuOS-machines. In `/etc/pacman.conf`:

```
[suos]
SigLevel = Optional TrustAll
Server = https://raw.githubusercontent.com/nzbsd/suos-pakketten/main/x86_64
```

Releases worden gebouwd met `suos-release` in de dev-omgeving.
