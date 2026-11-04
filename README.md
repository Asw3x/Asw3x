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

| Проект |  |
|---|---|
| **[writeups](https://github.com/Asw3x/writeups)** | Разборы CTF, лабораторий и реальных проектов: разведка - гипотезы - эксплуатация - как это чинить |
| **[external-pentest-playbook](https://github.com/Asw3x/external-pentest-playbook)** | Методология внешнего пентеста, написанная по следам реального проекта. |
| **[zimbra-ir-triage](https://github.com/Asw3x/zimbra-ir-triage)** | Автономный IR/форензик-триаж почтовых серверов Zimbra: поиск скомпрометированных ящиков по SASL-логам, Sieve-бэкдоров и always_bcc, web-shell'ов в Jetty, процессов из удалённых бинарей, сигнатуры известных RCE-CVE. Read-only, self-throttling |
| **[sast-scanner](https://github.com/Asw3x/sast-scanner)** | Статический анализатор: ядро отделено от UI, правила подгружаются из XML без перекомпиляции, severity и номера строк в отчёте. Вырос из университетского проекта |
| **[s365-triage](https://github.com/Asw3x/s365-triage)** | Разбирает скоуп программ bug bounty из текстовых описаний (отделяя «вне области» от «в области») и ранжирует программы по доле принятых отчётов, ширине скоупа и скорости триажа |
| **[DomofonAPPerfect](https://github.com/Asw3x/DomofonAPPerfect)** | Альтернативный Android-клиент для домофонов DOMONAP на Kotlin/Compose. API восстановлен реверсом: [как это делалось](https://github.com/Asw3x/DomofonAPPerfect/blob/main/REVERSE.md) |
| **[appsec-notes](https://github.com/Asw3x/appsec-notes)** | Личная база знаний по веб-уязвимостям и чеклисты |

---

### Bug Bounty

**Яндекс** — [Hall of Fame, 2026 Q1, 66 место](https://yandex.ru/bugbounty/i/hall-of-fame)

| Severity | CVSS | Отчёт |
|---|---|---|
| High | 7.5 | `BOUNTYREPORT-12149` |
| Medium | 4.3 | — |
| Low | 3.1 | — |

**Standoff365** — [профиль](https://standoff365.com/profile/Asw3x/), 11 отчётов

| Severity | CVSS | Цель |
|---|---|---|
| High | 8.1 | `hh.ru` |
| High | 7.5 | `vkvideo.ru` |
| High | 7.1 | `wildberries.ru` |
| High | 7.1 | `vk.com` |
| Medium | 5.3 | `okko.tv` |

**Вне программ** — Kleek (финтех), логическая ошибка в расчёте суммы платежа. Отправил в
поддержку, передали в разработку, исправлено.

### CTF

Играю в команде **[PrishliPohavaTeam](https://ctftime.org/team/450174)**.

- SolarCTF 2026 — 6 место
- Кубок CTF России 2026 — 11 место

Разборы задач — в [writeups](https://github.com/Asw3x/writeups#ctf).

### Инструменты и стек

`Burp Suite` · `ffuf` · `nuclei` · `nmap` / `masscan` · `Semgrep` · `Impacket` / `netexec` ·
`jadx` / `apktool` / `IDA Pro` · `Python` · `Kotlin` · `C#` · `Linux` · `Docker` · `Git`

Пишу собственные скиллы и агентов для AI-ассистентов под задачи пентеста.

Ищу уязвимости и разбираю последствия: IR-триаж почтовых серверов, поиск персистентности.
И пишу прод — [marellshop.ru](https://marellshop.ru), интернет-магазин под ключ: архитектура,
БД, деплой, поддержка.

Учусь в РТУ МИРЭА, Институт кибербезопасности — «Безопасность программных решений».
