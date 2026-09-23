# 🧮 Age-Calculator-Tkinter

Krijuar nga **Erion Nezha** — © 2026

**Llogaritës moshe** me ndërfaqe grafike — programi origjinal është shkruar në
**Python me tkinter**.

## 🎬 Demo live

https://erionnezha.github.io/Age-Calculator-Tkinter/

⚠️ **SIMULIM** — demo-ja ekzekutohet në browser me të njëjtën logjikë llogaritjeje
si origjinali. Programi origjinal kërkon **Python + tkinter**:

```bash
python Age_Calculator_GUI.py
```

## 🧠 Si funksionon

1. Fut **datën e lindjes** (ditë / muaj / vit).
2. Fut **datën e dhënë** (ditë / muaj / vit).
3. Kliko **"Llogarit moshën"** — rezultati shfaqet në vite, muaj dhe ditë.

Logjika ndjek saktë `calculateAge()` të origjinalit: huazim ditësh nga muaji
i lindjes dhe huazim muajsh nga viti, kur dita/muaji i lindjes e kalon datën e dhënë.

- `checkError()` — nëse ndonjë fushë është bosh, shfaqet mesazh gabimi dhe
  pastrohen të gjitha fushat (si `messagebox.showerror` në origjinal).
- `clearAll()` — butoni **"Pastro të gjitha"** zbraz të 9 fushat.

## 📁 Origjinali

`original/Age_Calculator_GUI.py` — kodi burim Python/tkinter, i paprekur.

## 📝 Licenca / Provenjenca

Shiko `PROVENANCE_LICENSE.txt`.
