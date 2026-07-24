# Windows Debloat Toolkit (Pulse Edition)

A safe, stable, and fully restorable Windows debloat toolkit using **ChristTitus Safe Style (Appx‑only)** removal.  
Designed to debloat Windows **without breaking Start Menu, Taskbar, Search, Settings, Explorer, hardware, or system features**.

This toolkit includes:

- **Gamer Debloater**
- **Normal Debloater**
- **Restore Everything**

All scripts include:

- Admin check  
- Restore point creation (first step)  
- No errors shown  
- Safe Appx-only removals  
- Copilot disabled  
- Notepad protected  
- Edge kept  
- Optional OneDrive removal prompt at the end  
- Fully restorable system  

---

## 🔰 Safety Overview

This toolkit uses **SAFE Titus-style debloating**, meaning:

- Only **AppxPackage** (per-user apps) are removed  
- **ProvisionedPackages are NOT removed**  
- **System frameworks are NOT removed**  
- **ShellExperienceHost is NOT touched**  
- **StartMenuExperienceHost is NOT touched**  
- **EdgeWebView2 is NOT touched**  
- **Microsoft.UI.Xaml is NOT touched**  
- **Windows Search framework is NOT touched**  
- **Drivers and hardware services are NOT touched**

This ensures:

- Start Menu works  
- Taskbar works  
- Settings app works  
- Search works  
- Explorer works  
- Windows boots normally  
- Hardware works normally  
- Restore script can fix everything  

---

# 1️⃣ Gamer Debloater

### Purpose
Debloat Windows while keeping all gaming-related features intact.

### Removes (Appx-only)
- 3D Viewer  
- Mixed Reality Portal  
- Paint 3D  
- People  
- Skype  
- OfficeHub  
- Solitaire  
- FeedbackHub  

### Keeps
- Xbox apps  
- Game Bar  
- Gaming Services  
- Clipchamp  
- Notepad  
- Edge  
- All system components  

### Other Actions
- Disables ads & suggestions  
- Disables telemetry tasks  
- Disables Copilot  
- Creates restore point first  
- No errors shown  

### OneDrive Behavior
At the end of the script:

```
Remove OneDrive? (Y/N)
```

- **Y** → OneDrive is removed  
- **N** → OneDrive stays fully enabled  

### Safety
- 100% safe  
- Fully restorable using Restore Everything  

---

# 2️⃣ Normal Debloater

### Purpose
More aggressive debloat for non-gamers.

### Removes (Appx-only)
Everything in Gamer Debloater PLUS:

- Cortana  
- Windows Maps  
- Weather  
- Alarms  
- Camera  
- Mail & Calendar  
- Xbox apps  
- GamingApp  

### Keeps
- Edge  
- Notepad  
- All system components  

### Other Actions
- Disables ads & suggestions  
- Disables telemetry tasks  
- Disables Copilot  
- Creates restore point first  
- No errors shown  

### OneDrive Behavior
At the end of the script:

```
Remove OneDrive? (Y/N)
```

- **Y** → OneDrive is removed  
- **N** → OneDrive stays fully enabled  

### Safety
- 100% safe  
- Fully restorable using Restore Everything  

---

# 3️⃣ Restore Everything

### Purpose
Fully restore all Appx packages removed by the debloaters.

### Actions
- Creates restore point first  
- Re-registers all Appx packages for all users  
- Re-enables ads/sync notifications  
- Re-enables telemetry tasks  
- Re-enables Copilot  
- Re-installs OneDrive  
- No errors shown  

### Limitations
- Can restore everything removed by Appx-only debloat  
- Cannot restore apps removed via ProvisionedPackage removal  
  (this toolkit does NOT use that method)

### Safety
- 100% safe  
- Fully compatible with both debloaters  

---

# 🧩 Why This Toolkit Is Safe

This toolkit **never** removes:

- StartMenuExperienceHost  
- ShellExperienceHost  
- EdgeWebView2  
- Microsoft.UI.Xaml  
- Windows Search framework  
- System drivers  
- Hardware services  
- ProvisionedPackages  
- Anything required for Windows to boot or run  

This guarantees:

- No Start Menu breakage  
- No Taskbar breakage  
- No Settings app breakage  
- No Search breakage  
- No Explorer breakage  
- No hardware issues  
- No Windows instability  

---

# ☁️ OneDrive Behavior

At the end of each debloater:

```
Remove OneDrive? (Y/N)
```

- **Y** → OneDrive is removed safely  
- **N** → OneDrive stays fully enabled  

This gives users full control.

---

# 🤖 Copilot Behavior

Copilot is disabled using a safe registry flag:

```
TurnOffWindowsCopilot = 1
```

This does **not** remove any system components and is fully reversible.

---

# 📝 Notepad Protection

Notepad (`Microsoft.Windows.Notepad`) is always kept.  
It is never removed or modified.

---

# 🌐 Edge Protection

Microsoft Edge is always kept.  
It is never removed or disabled.

---

# ✔ End of README
