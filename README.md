# Útskýringar á hvað við gerðum

1. Við settum upp nginx, mysql og php fyrir https://filedrop.fisedush.com, https://gudmunduro.com og fleira.

2. Bjuggum til þrjár möppur og settum og settum owner og group á því í www-data:nginx og permission á öllum í 770.

3. Bjuggum til user pythonapps og settum hann sem owner á öllum python vef öppum.

![Nginx config](https://github.com/gudmunduroh/kest_lokaverkefni/raw/master/images/nginx.png)

4. Gerðum alla config file-ana fyrir vefsíðurnar.

![Nginx config](https://github.com/gudmunduroh/kest_lokaverkefni/raw/master/images/nginx-conf.png)

5. Settum upp ssl certificate frá Let's Encrypt.

6. [Bjuggum til script til að flýta fyrir að setja upp vefsíður](https://github.com/Gudmunduro/addsite-cmd)

7. Settum upp ssh keys á servernum og settum PasswordAuthentication í no til að það væri bara hægt að nota ssh keys og PermitRootLogin í Root til að það væri ekki hægt að logga sig inn með root.

![Nginx config](https://github.com/gudmunduroh/kest_lokaverkefni/raw/master/images/ssh_key.png)

8. Breyttum ssh port í 2020.

9. Bjuggum til nokkra sql usera.

10. Bjuggum til userana Gudmundur og Helgi og settum þá inn í nginx groupuna til að þeir hefðu aðgang að /var/www.

11. Settum hostname í fisedush.

12. Settum upp Swift og Vapor.

![Nginx config](https://github.com/gudmunduroh/kest_lokaverkefni/raw/master/images/swift.png)

13. Byrjuðum að búa til vefsíðau fyrir management á servernum en náðum ekki að klára hana.

