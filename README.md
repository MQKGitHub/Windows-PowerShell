### 🛡️ Windows PowerShell

**Room:** [Windows PowerShell — TryHackMe](https://tryhackme.com/room/windowspowershell)  
**Status:** ✅ Completed  
**Date:** *14 May 2025*  

### 🎯 Objective
This room introduced PowerShell as a powerful automation and configuration management tool. The goal was to understand its object-oriented nature, learn fundamental cmdlets, and explore practical applications in system administration and cyber security.

---

### 🗝️ Key Concepts  
- **Object-Oriented Shell** — PowerShell handles data as objects with properties and methods rather than plain text.  
- **Verb-Noun Cmdlets** — Commands follow a consistent `Verb-Noun` structure (e.g., `Get-Process`, `Set-Location`).  
- **Pipeline Power** — Objects can be passed between cmdlets using the `|` operator for complex operations.  
- **Remote Management** — `Invoke-Command` enables executing scripts on remote systems.  
- **Extensibility** — Additional modules can be installed from repositories like PowerShell Gallery.  

---

### 🛠️ Tools Used
- **Core Cmdlets** — `Get-Command`, `Get-Help`, `Get-Alias` for discovery and learning  
- **File Management** — `Get-ChildItem`, `New-Item`, `Copy-Item`, `Remove-Item`  
- **System Analysis** — `Get-ComputerInfo`, `Get-Process`, `Get-Service`  
- **Network Tools** — `Get-NetIPConfiguration`, `Get-NetTCPConnection`  
- **Filtering Cmdlets** — `Where-Object`, `Select-Object`, `Sort-Object`  

---

### ⚠️ Challenges Faced
- Initially confusing object-oriented approach for CLI users  
- Remembering correct parameter syntax for complex cmdlets  
- Differentiating between similar-sounding cmdlets (e.g., `Select-Object` vs `Where-Object`)  
- Overcame by:  
  - Using `Get-Help` extensively  
  - Practising with simple pipelines first  

---

### 🧠 What I Learned
- How PowerShell's object orientation enables more powerful operations than traditional CLI  
- The importance of the `Verb-Noun` naming convention for discoverability  
- Techniques for filtering and sorting object collections  
- How to retrieve detailed system and network information  
- Basic scripting concepts and their security applications  
- The difference between aliases (e.g., `dir`) and native cmdlets (`Get-ChildItem`)  

---

### 🌐 Real-World Application:
> PowerShell is indispensable for IT professionals and security practitioners. Its ability to manage systems at scale makes it valuable for:
> - **Blue Teams**: Automating security monitoring and incident response  
> - **Red Teams**: Conducting penetration tests and post-exploitation  
> - **SysAdmins**: Managing enterprise environments through remote execution  
> The object-oriented approach enables complex data analysis that would be cumbersome with traditional shells.

---

### 💭 Reflections:
- Most surprising: How much more powerful PowerShell is compared to CMD  
- Most valuable: Learning to chain cmdlets with pipelines  
- Key insight: "Mastering PowerShell transforms you from a basic user to a systems automation expert"  
- Biggest challenge: Transitioning from text-based to object-based thinking  
