### BUG Elementary Freya

Mesmo depois de forçar o sistema a usar pt_BR, na página de login, a data, Guest (convidado) e etc, aparecem em inglês.

Borá acertar isso aê?! :shipit:

Abra o terminal e digite:
```
sudo gedit /etc/environment
```

Vai ter algo:
```
PATH="/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games"
```

Adicione isso no arquivo:
```
LC_ALL="pt_BR.UTF-8"
```

Salve e feche! Reinicie e veja amágica acontecer!

Obs. Pode rodar um update, upgrade depois um dist-upgrade bem marotamente!
