⚠️ **CRITICAL WARNINGS**

## ⚠️ BEFORE USING THIS TOOL

### 1. CREATE A SYSTEM RESTORE POINT FIRST
This is **MANDATORY** before running this tool:
```cmd
Shift + Right-click on This PC → Create a restore point
```
OR create a full system image:
```cmd
Control Panel → Backup and Restore → Create a system image
```

**Do not proceed without a backup/restore point. You may not be able to undo changes.**

---

### 2. ⛔ DO NOT USE ON ENTERPRISE-MANAGED DEVICES

**DO NOT RUN THIS TOOL IF:**
- Your device is managed by an organization (hospitals, corporations, government agencies, schools, etc.)
- Your device is domain-joined (check: Settings → System → About)
- You are on a corporate network
- You have an MDM (Mobile Device Management) profile installed
- Your device uses Group Policy for security management

**WHY?**
- Enterprise devices have security requirements mandated by compliance standards
- Removing Windows Defender may violate organizational security policies
- This could trigger alerts in your organization's security monitoring systems
- You may face disciplinary action or data security violations
- Hospital and healthcare systems require specific security controls (HIPAA, etc.)
- Educational institutions require Defender for student/staff protection

---

### 3. WHAT THIS TOOL DOES

**Targets for removal/disabling:**
- ✓ Windows Defender Antivirus (WinDefend service)
- ✓ Windows SmartScreen
- ✓ Windows Security App (SecHealthUI)
- ✓ Security Health Service

**DOES NOT target:**
- ✗ Reliability Monitor (preserved)
- ✗ Windows Update
- ✗ Control Panel security settings (mostly preserved)

---

### 4. RISKS

- System may become vulnerable to malware
- Windows Update behavior may change
- Some Windows features may not function properly
- Difficult or impossible to reverse without restore point
- May conflict with other security software

---

### 5. PERSONAL USE ONLY

This tool is intended for personal, non-enterprise devices only:
- Home computers
- Personal laptops
- Dev machines that are NOT on a corporate network

---

**⚠️ You assume all responsibility for using this tool. Always create a restore point first.**
