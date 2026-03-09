# 🔒 Null

> PowerShell script to **disable NULL sessions** for SMB — RestrictAnonymous, RestrictNullSessAccess. Also sets battery power plan.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🚫 **RestrictAnonymous** | LanmanServer, Lsa |
| 🚫 **RestrictNullSessAccess** | Netlogon |
| 📋 **gpupdate /force** | Applies Group Policy |
| 🔋 **powercfg** | Sets SUB_BATTERY active |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Privileges** | Administrator |

---

## 🚀 Usage

```powershell
.\Null.ps1
```

---

<p align="center">
  <sub>🛡️ Gorstak Security Hardening</sub>
</p>
