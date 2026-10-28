# MobileEntry (AGREED) - Вход на мобильную визитку ALIS

m.alis.live открывает https://alis.live/m/ — мини-интерфейс SlotB с общим медиакэшем полной страницы. Страница вызывает location.replace с сохранением query и hash; адрес назначения фиксирован. Без JavaScript работают meta refresh на корень мини-версии и обычная ссылка. Это клиентский переход GitHub Pages, а не HTTP 301.

Репозиторий публикации — 296936/alis-mobile, ветка master, корень. Перед публикацией накладываются CNAME и .nojekyll из ../../wslots_b4deploy/alis-mobile. Pages использует Custom domain=m.alis.live, DNS CNAME m в зоне alis.live указывает на 296936.github.io. HTTPS включается после готовности сертификата GitHub. Исходники MP3, тексты и данные визитки здесь не хранятся.
