# Bluescreen Roulette (Windows Crash Trigger)

> A proof-of-concept Python script simulating a destructive malware scenario with a random outcome. Designed for **educational purposes** only. **Run exclusively in a virtual machine** or isolated environment.

---

## ⚠️ WARNING

This script randomly decides whether or not to **crash** the system by triggering a blue screen of death (BSOD) on Windows. 

- If the result is **6**, it causes a BSOD, effectively crashing the system.
- If the result is **1–5**, nothing happens, and the script terminates harmlessly.

**Do not run on production machines**. Only run in a safe, virtualized environment.

## 🛠️ How to Use

1. Clone the repository
2. Run the script in an isolated virtual machine:

```bash
python bluescreen_roulette.py
```

> Always run this script in a **sandboxed environment** to avoid any potential damage to your actual operating system.

---

## 🧑‍💻 Author

**JancoNel**  

---

> **Disclaimer:** This code is intended for **ethical hacking**, **educational purposes**, and **red team simulations**. Misuse outside of secure, isolated environments is not the responsibility of the author.
