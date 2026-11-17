RublCompany — дополнительные файлы сайта

Загрузите все пять файлов в корень репозитория GitHub Pages (рядом с index.html):
about.html, contact.html, privacy.html, robots.txt, sitemap.xml.

На GitHub: откройте репозиторий → Add file → Upload files → выберите файлы → Commit changes.

После публикации проверьте:
https://rublcompany.github.io/about.html
https://rublcompany.github.io/contact.html
https://rublcompany.github.io/privacy.html
https://rublcompany.github.io/robots.txt
https://rublcompany.github.io/sitemap.xml

Ещё нужно добавить ссылки на страницы в меню/подвал index.html:
<a href="/about.html">О проекте</a>
<a href="/contact.html">Контакты</a>
<a href="/privacy.html">Политика конфиденциальности</a>

Если в index.html уже есть старый адрес hello@rublcompany.example, замените его на указанный вами адрес.

SEO для главной страницы: внутри <head> добавьте (если таких тегов ещё нет):
<meta name="description" content="Практические советы по Reels, коротким видео, контенту и продвижению малого бизнеса.">
<link rel="canonical" href="https://rublcompany.github.io/">
<meta property="og:title" content="RublCompany — короткие видео и продвижение">
<meta property="og:description" content="Идеи, инструкции и инструменты для создания контента и продвижения малого бизнеса.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://rublcompany.github.io/">

Политика конфиденциальности — стартовый шаблон. Перед подключением рекламной сети или аналитики дополните его сведениями о конкретном поставщике, cookie и согласии посетителей. Не обещает одобрение рекламной сети.
