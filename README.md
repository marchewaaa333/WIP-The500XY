# 🖨️ The500XY (WIP)
**500x500 Open-Source CoreXY Printer Based on Rook 2020**

---

## 🔥 About

Around **December 2024**, I kicked off my 3D printing business. I needed machines — a lot of them.  
And since I’ve been building printers since the **Prusa i2** era, I figured:  
> *“Screw it, let’s build something big.”*

That’s how **LanternXY** was born — a basic CoreXY printer.  
But I never made it public because, let’s be honest, it just wasn’t sturdy enough.  
Good idea, not-so-good frame.

**So I rebuilt it**. I used the awesome open-source **Rook 2020** design as the base, improved the rigidity,  
and gave it a new name and identity: **The500XY**.

---

## 📏 Build Volume

**483 × 483 × 600 mm**  
*Big enough to print a helmet, sword, or hell — even a small chair.*

---

## 🛠️ Linear Rails

- **X-axis:** `MGN9C`
- **Y-axis:** `MGN12C`
- **Z-axis:** `MGN9C x3`

---

## 🧱 Frame – 2020 Aluminium Extrusion

### X-Axis:
- `6 × 633mm` extrusion  
- `1 × 583mm` extrusion  
- `1 × 548mm` MGN9C rail

### Y-Axis:
- `4 × 633mm` extrusion  
- `2 × 483mm` extrusion  
- `2 × 633mm` MGN12C rails

### Z-Axis:
- `5 × 700mm` extrusion  
- `3 × 700mm` MGN9C rails

---

## 📝 Changelog

*WIP – will be added soon*

---

## 💬 License & Credits

Based on the awesome [Rook 2020 Scalable]([https://github.com/GadgetAngel/rook](https://www.printables.com/model/482283-rook-2020-scalable-mk1)) design.  

Feel free to fork, remix, improve — just don’t be a dick about it 😉

---

## 📸 Gallery / Media

*(Coming soon — will add build pics, renders, and maybe a timelapse video)*

---
## 🧠 Electronics & Software

This machine isn’t just muscle — it's got brains too.

### 🔌 Main Components:
- 🧠 **Mainboard**: BigTreeTech **Octopus v1.1**
- 🖥️ **Display**: BTT **HDMI5** touchscreen
- 🍓 **Host**: Raspberry Pi 4 (4GB or 8GB)
- 🌀 **Motors**: Standard **NEMA17** stepper motors
- 🧠 **Firmware**: [**Klipper**](https://www.klipper3d.org/) (because Marlin just isn’t fast enough for this beast)

Everything runs through **Fluidd** or **Mainsail** (your choice) via Klipper.  
Fast prints, smart macros, easy tuning — and yeah, it can scream.

---

## ⚙️ TODO (Next Steps)

- [ ] Upload STEP/STL files  
- [ ] Add full wiring diagram  
- [ ] Include `printer.cfg` example for Klipper  
- [ ] Document endstops, probes, fans, heaters, etc.  
- [ ] Full BOM with part links  


---

Made with way too much white and pink monster energy drinks 🥤 and a bit of insanity  
— `@marchewaaa333`
