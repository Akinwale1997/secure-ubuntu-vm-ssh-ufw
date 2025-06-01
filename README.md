# 🔐 Secure Ubuntu VM with SSH Hardening and UFW Firewall on Azure

This project demonstrates how to securely deploy and harden an Ubuntu virtual machine (VM) on Microsoft Azure using SSH key authentication, UFW firewall configuration, and basic Linux security hygiene.

---

## ✅ Real-Life Scenario

Client: *Kik Perfume – An online perfume store*

Scenario:  
Kik Perfume wants to host its product catalog and internal management system on a secure cloud server. As their cloud security engineer, your task is to:

- Deploy a secure Ubuntu VM.
- Harden SSH access (disable root login and enforce key-based login).
- Set up firewall rules to only allow essential traffic (SSH, HTTP, HTTPS).
- Validate that no unauthorized users or services are active.

---

## ⚙️ Technologies Used

- Microsoft Azure
- Ubuntu 22.04 LTS
- SSH Key Pair (RSA)
- UFW (Uncomplicated Firewall)
- Azure CLI
- GitHub (for documentation)

---

## 🧰 Step-by-Step Implementation

### 1. ✅ Deploy Ubuntu VM via Azure Portal  
![Step 1 - VM Deployed](01-vm-overview-deployed.png)

### 2. ✅ Connect to the VM via Azure CLI  
![Step 2 - Connected to VM](02-connected-to-linux-vm.png)

### 3. ✅ Run Basic Linux Commands  
![Step 3 - Basic Linux Commands](03-basic-linux-commands.png)

### 4. ✅ Diable Root Login in SSH Config  
![Step 4 - No Failed Login Attempts](04-failed-login-attempts-none.png)

### 5. ✅ Confirmed Failed Login Attempts Are Blocked  
![Step 5 - SSH Config Updated](linuxVM_SSH_Config_Validated.png)

### 6. ✅ Set up firewall  
![Step 6 - UFW Firewall Enabled](06-UFW-FirewallRules-Enabled.png)
