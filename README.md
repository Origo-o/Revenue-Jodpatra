# राजस्व अपील कंप्लायन्स · Compliance Suite

One self-contained web app for **Maharashtra District Collector RTS Revenue Appeal** filings.
Single file — no internet needed, works in any modern browser (Chrome/Edge/phone browser).

---

## ▶ Open it
1. Download **`Revenue_Appeal_Compliance_Suite.html`**.
2. Double-click → opens in your browser. That's it.

> Data is saved **on this device** (browser storage). Use **सेटिंग्ज → Backup** to move it to another computer or keep a safe copy.

---

## The app is now simpler — just 3 sections + a client editor

### 🏠 मुख्य / Home
- Summary: total clients, **pending vs settled** counts, outstanding amount.
- **Add client** (name, case no, date, court, client mobile/email, **advocate name & mobile**).
- Client list with **एकूण / भरले / शिल्लक / स्थिती** and quick actions:
  **उघडा · 📲 WhatsApp · पावती · काढा**. Click the status pill to toggle प्रलंबित/निकाली.

### 👤 Client editor (open a client)
- **Fixed billing** — this replaces the old confusing checkbox+amount bug:
  - Tick a box **or press +/−** to avail an item → amount = qty × rate (auto).
  - Type the quantity → it avails & recalcs live (no more ₹0 totals).
  - **एकूण**, **भरले (paid)**, and **शिल्लक (balance)** update instantly.
- Buttons: **📲 WhatsApp ग्राहक**, **📲 WhatsApp वकील**, **📷 पावती इमेज**, **🖨 पावती PDF**.

### 📋 फॉर्म / Forms (official fillable Marathi forms)
- **छाननी पत्रक** (16 points · होय/नाही/लागू नाही), **जोडपत्र-२ (सत्यापन)**, **जोडपत्र-३ (शपथपत्र)**, **जोडपत्र-४ (फेरफार)**.
- Type into underlined blanks → **🖨 छापा / PDF** (A4) or **📲 WhatsApp**; saved per client & date.

### ⚙️ सेटिंग्ज / Settings
- Office / filer details, currency.
- **Compliance list** — add/edit/remove items, change **दर** & **प्रमाण** (these are the settings you asked for).
- **Backup**: **⬇ JSON** · **⬇ CSV (Excel)** · **⬇ PDF रिपोर्ट** (print → Save as PDF) · **आयात करा** · **सर्व पुसा**.

---

## 📲 WhatsApp sharing
- **WhatsApp ग्राहक / वकील** → opens WhatsApp with the **itemised receipt message** (client) or **advocate copy** (advocate's number).
- **📷 पावती इमेज** → on a **phone**, shares the receipt as a **picture (PNG)** via the native *Share* sheet (WhatsApp available there); on desktop it downloads the image to attach in WhatsApp Web.
- Forms can also be sent via **📲 WhatsApp** (text with client details).

## 💾 Backup formats
- **JSON** — full app data (import later to restore).
- **CSV** — opens in Excel; one row per client+item (rate, qty, amount, paid, balance, status).
- **PDF रिपोर्ट** — prints the whole client register; use the print dialog's **“Save as PDF”**.

---

## Notes
- Item names/prices from the handwritten sheet are **estimated** — adjust them in **सेटिंग्ज → कंप्लायन्स यादी**.
- The official form text is a faithful editable copy to fill & print; you can still print the original scanned PDF as-is.
- WhatsApp text share works everywhere; **image share works on mobile** (and downloads on desktop). True **PDF** output is via **🖨 Save as PDF**.
