# healthhub-keys

Открытый ключ, которым [@shnyakov](https://github.com/shnyakov) подписывает выписки своих анализов
в формате [SMART Health Cards](https://spec.smarthealth.cards) для Apple Health. Выписки собирает
HealthHub — личное приложение-архив медицинских документов — из бланков лабораторий.

- **Издатель (iss):** `https://shnyakov.github.io/healthhub-keys`
- **Ключ (JWKS):** [`/.well-known/jwks.json`](https://shnyakov.github.io/healthhub-keys/.well-known/jwks.json)

**Что значит подпись:** карточку выпустил владелец этого аккаунта, и после подписи её не
меняли. **Чего подпись не значит:** что значения подтверждены лабораторией или врачом — это
перенос из бланка, а не документ лаборатории.

Медицинских данных здесь нет — только открытый ключ. Ключи отсюда не удаляются: удаление сделало
бы уже выданные карточки непроверяемыми.

---

Public key used by @shnyakov to sign personal lab-result exports (SMART Health Cards) for Apple
Health, produced by HealthHub, a personal medical-records app. A valid signature means the card
was issued by this account and has not been altered; it does not mean a laboratory or clinician
attested the values. No health data is stored here.
