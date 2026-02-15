# 🔌 Smart-USB-Hub 
> Because I wanted a hub that actually looks cool and doesn't break.

So, I got tired of those cheap plastic USB hubs that die after a week. I decided to just make my own in KiCad. It’s got a mix of ports because, let’s be real, we’re all living in that annoying "half-USB-A, half-USB-C" era right now.

## **🛠️ The Specs**
**4 Ports Total:** Perfectly balanced, as all things should be.

**2x USB-A:** For your mouse, keyboard, or that random flash drive you found.

**2x USB-C:** For the modern stuff (and because flipping the plug 3 times is annoying).

**KiCad Design:** Everything is open sourced. You can build your own version. Or help by contributing

## Layouts
<img width="720" height="498" alt="Schematics Zoomed Out" src="https://github.com/user-attachments/assets/d9d42c4a-8c9a-4f58-ba39-60f19193f614" />
<img width="1051" height="538" alt="PCB Layout" src="https://github.com/user-attachments/assets/cff59f85-9b11-4e13-99b5-e39e89b6cfcd" />

## Renders
<img width="1170" height="618" alt="PCB Render Front View (KiCad)" src="https://github.com/user-attachments/assets/3bb0e337-45a4-4b29-b99c-d519dff1a002" />
<img width="1170" height="618" alt="PCB Render Back View (KiCad)" src="https://github.com/user-attachments/assets/7eb67205-7dda-4ca3-ab33-cd16f316e3cf" />

> will add blender renders when I have finished my other project

## **📁 What’s in here?**
**/PCB:** The actual board layout. I tried to keep it clean so it's easy to solder.

**/Schematic:** The "brain" map. Check it out if you want to see how the power flows.

**/production:** Necassary files to order your own PCB!

## **⚡ How to make one**
Order the Boards: Grab the Gerber files and send them to JLCPCB or PCBWay (or wherever you get your fix).

Buy the Parts: Check the BOM (Bill of Materials). Don't cheap out on the capacitors!

Solder it: Get your iron hot, put on some music, and try not to bridge the tiny pins on the USB-C ports (those things are a pain, honestly).

Plug it in: If it doesn't smoke, you did it!

## BOM Base
> The xlsx is alos in the root directory

If you're building this yourself, here is what you need to grab. I got most of my small parts from [duino.lk](https://www.duino.lk). WHich is a local-only for Sri Lanka. These components are THT which are easy to solder by yourself :D. Other components were ordered w/ PCBA.

| Product Name | Quantity | Source Link | Price (USD) |
| :--- | :---: | :--- | :--- |
| 220uF 16v Aluminum Electrolytic Capacitor | 8 | [duino.lk](https://www.duino.lk) | $0.40 |
| 10uF 25v Aluminum Electrolytic Capacitor | 8 | [duino.lk](https://www.duino.lk) | $0.25 |
| 104PF 0.1UF Ceramic Capacitor Disc | 20 | [duino.lk](https://www.duino.lk) | $0.20 |
| 1UF 50V Aluminum Electrolytic Capacitor | 4 | [duino.lk](https://www.duino.lk) | $0.15 |
| PCB (PCB + PCBA + SHIPPING) | 5 | JLC PCB | $78.00 |
| **Shipping (for duino.lk)** | - | - | $2.00 |
| **Exchange Tax?** | - | - | $5.00 |
| **Total** | | | **$86.00** |

## **🛑 Disclaimer**
If you solder something backwards and it smells like burning plastic... that's on you, bro. Double-check your polarity!
