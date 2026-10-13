<h1 align="center">Алексей Костин — asw3x</h1>

<p align="center">
  <b>Пентест полного цикла · AppSec · Bug Bounty</b><br>
  <sub>Москва · РТУ МИРЭА, ИКБ · <a href="https://t.me/xitsys">Telegram</a> · asw3x.is@gmail.com</sub>
</p>

---

Работаю пентестером: внешний периметр, веб и API, толстые клиенты, внутренняя сеть.
Параллельно — bug bounty: Hall of Fame Яндекса за 2026.

---

### Избранное

| Проект | Что это и зачем смотреть |
|---|---|
| **[writeups](https://github.com/Asw3x/writeups)** | Разборы CTF, лабораторий и собственных проектов: разведка → гипотезы → эксплуатация → как это чинить |
| **[external-pentest-playbook](https://github.com/Asw3x/external-pentest-playbook)** | Методология внешнего пентеста, написанная по следам реального проекта. |
| **[zimbra-ir-triage](https://github.com/Asw3x/zimbra-ir-triage)** | Автономный IR/форензик-триаж почтовых серверов Zimbra: поиск скомпрометированных ящиков по SASL-логам, Sieve-бэкдоров и `always_bcc`, web-shell'ов в Jetty, процессов из удалённых бинарей, сигнатуры известных RCE-CVE. Read-only, self-throttling — безопасно гонять на проде |
| **[sast-scanner](https://github.com/Asw3x/sast-scanner)** | Статический анализатор: ядро отделено от UI, правила подгружаются из XML без перекомпиляции, severity и номера строк в отчёте. Вырос из университетского проекта |
| **[s365-triage](https://github.com/Asw3x/s365-triage)** | Разбирает скоуп программ bug bounty из текстовых описаний (отделяя «вне области» от «в области») и ранжирует программы по доле принятых отчётов, ширине скоупа и скорости триажа |
| **[DomofonAPPerfect](https://github.com/Asw3x/DomofonAPPerfect)** | Альтернативный Android-клиент для домофонов DOMONAP на Kotlin/Compose. API восстановлен реверсом: [как это делалось](https://github.com/Asw3x/DomofonAPPerfect/blob/main/REVERSE.md) |
| **[appsec-notes](https://github.com/Asw3x/appsec-notes)** | Личная база знаний по веб-уязвимостям и чеклисты |

---

### Bug Bounty

**Яндекс** — [Hall of Fame, 2026 Q1, 66 место](https://yandex.ru/bugbounty/i/hall-of-fame)

- Semi-Blind SSRF (`BOUNTYREPORT-12149`)
- Утечка IP клиента
- Content Spoofing

**Standoff365** — [профиль](https://standoff365.com/profile/Asw3x/), 11 отчётов

- `hh.ru` - IDOR, утечка ключей API
- `vkvideo.ru` — в регулярке валидации пути нет якоря `$`, поэтому `../` выводит за пределы
  разрешённой директории к любым эндпоинтам домена
- `okko.tv` — CRLF
- `wildberries.ru`, `vk.com` — CORS с `Access-Control-Allow-Credentials: true`
  и отражением произвольного `Origin`

**Вне программ** — Kleek (финтех): отрицательные чаевые уменьшали сумму платежа. Отправил в
поддержку, передали в разработку, исправлено.

### Инструменты и стек

`Burp Suite` · `ffuf` · `nuclei` · `nmap` / `masscan` · `Semgrep` · `Impacket` / `netexec` ·
`jadx` / `apktool` / `IDA Pro` · `Python` · `Kotlin` · `C#` · `Linux` · `Docker` · `Git`

Пишу собственные скиллы и агентов для AI-ассистентов под задачи пентеста.

Ищу уязвимости и разбираю последствия: IR-триаж почтовых серверов, поиск персистентности.
И пишу прод — [marellshop.ru](https://marellshop.ru), интернет-магазин под ключ: архитектура,
БД, деплой, поддержка.

Учусь в РТУ МИРЭА, Институт кибербезопасности — «Безопасность программных решений».
