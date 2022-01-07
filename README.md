# Pi-hole White Lists
This contains my custom whitelists for Pi-hole.

*I borrowed some whitelists from https://discourse.pi-hole.net/t/commonly-whitelisted-domains/212 and https://wally3k.github.io/*

## TODO:
Note to myself to add whitelists from the following sites...
* https://discourse.pi-hole.net/t/commonly-whitelisted-domains/212
* https://wally3k.github.io/

## Google Services

### Google Maps

```
pihole -w clients4.google.com
pihole -w clients2.google.com
```

### YouTube History

```
pihole -w s.youtube.com
pihole -w video-stats.l.google.com
```

### Google Play

```
pihole -w android.clients.google.com
```


## Microsoft

### Windows (Verifies Internet Connectivity)

```
pihole -w www.msftncsi.com
```

### Microsoft Web Pages (Outlook, Office 365, Live, Mic)

```
pihole -w outlook.office365.com
pihole -w products.office.com
pihole -w c.s-microsoft.com
pihole -w i.s-microsoft.com
pihole -w login.live.com
```

### Backup Bitlocker Recovery Key to Microsoft Account
```
pihole -w g.live.com
```

### Windows Store
```
pihole -w dl.delivery.mp.microsoft.com
pihole -w geo-prod.do.dsp.mp.microsoft.com
pihole -w displaycatalog.mp.microsoft.com
```

### Skype

```
pihole -w s.gateway.messenger.live.com
pihole -w ui.skype.com
pihole -w pricelist.skype.com
pihole -w apps.skype.com
pihole -w m.hotmail.com
pihole -w s.gateway.messenger.live.com
pihole -w sa.symcb.com s{1..5}.symcb.com
```
