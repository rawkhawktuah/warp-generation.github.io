# Зеркало WARP Генератора от сообщества!

<img width="1300" height="600" alt="1000032073" src="https://github.com/user-attachments/assets/4e45d895-7f0c-42c2-b280-1e21a2055453" />

### Что такое WARP?

**WARP** – это бесплатный VPN от Cloudflare, который проксирует все ваши интернет запросы через свои CDN, которые располагаются во всем мире. Данный VPN - **НЕ МЕНЯЕТ** вашу страну, если находитесь в России - будет IP-адрес России (итак далее)

В данном README.md будет написано как сделать Deploy этого сайта на Vercel, CF Pages (Workers), Netlify.
## Начинаем!
### 1. 🌟 Vercel! (Рекомендуется)
Плюсы:
1. Vercel пока-что не заблокирован РКН
2. Удобно развернуть через него своё зеркало
3. Делается все легко, двумя кнопками мыши.
4. Сайт легко обновляется, если появляются новые коммиты.
5. Можно сделать Роллбэк, если сайт по какой-то причине не работает, или поломан скрипт.

Минусы:
1. Бесплатный план от Vercel предлагает только 100 ГБ трафика на ваш сайт, поэтому если ваш сайт выдаёт ошибку при входе – дело в том, что вы достигли лимита по трафику.

### Deploy сайта с Vercel:
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Frawkhawktuah%2Fwarp-generation.github.io)

### Cloudflare Pages!
Плюсы:
1. Стабилен, кэшируется в 300+ серверах в крупных городах по всему миру!
2. **БЕЗЛИМИТНЫЙ ТРАФИК, ДАЖЕ НА БЕСПЛАТНОМ ТАРИФЕ**
3. Тоже лёгок в освоении.
4. Сайт обновляется, когда появляется новый коммит

Минусы:
1. Подсети Cloudflare - забанены РКН, поэтому ваш провайдер прогрузит только 16 КБит, из-за чего ваш сайт будет максимум в формате __plaintext__.

### Deploy сайта с Cloudflare:
[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/rawkhawktuah/warp-generation.github.io)

### Netlify
Плюсы:
1. Легок в освоении
2. Щедрый бесплатный план, как у Cloudflare.
3. Есть роллбэк

Минусы:
1. Заблокированы IP-адреса РКНом
2. Лимит трафика 100 ГБ, как и у Vercel (при превышении - сайт автоматически отключается)

### Deploy сайта с Netlify:
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/rawkhawktuah/warp-generation.github.io)
