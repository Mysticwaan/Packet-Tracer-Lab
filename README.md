# 🛰️ Cisco Packet Tracer: Basic Lab Tutorial

Welcome to the **Cisco Packet Tracer** beginner tutorial! This guide walks you through installing Packet Tracer and creating your first basic networking lab.

---

## 📥 1. Installation

### ✅ Requirements
- A **Cisco Networking Academy** account ([Sign up here](https://www.netacad.com/))
- Windows, macOS, or Linux system

### 🔧 Steps
1. Go to [https://www.netacad.com/portal/resources/packet-tracer](https://www.netacad.com/portal/resources/packet-tracer)
2. Sign in and download the latest version of Cisco Packet Tracer.
3. Install it on your system following the on-screen instructions.
4. Launch the app and sign in using your NetAcad credentials.

---

## 🧪 2. Creating Your First Basic Lab

We’ll simulate a basic network with:
- 2 PCs
- 1 Switch
- IP Configuration
- Ping test

### 🛠️ Steps

#### Step 1: Add Devices
1. Open Packet Tracer.
2. From the **bottom left pane**, choose:
   - **End Devices** > Drag **2 PCs** onto the workspace.
   - **Switches** > Drag **1 Switch (e.g., 2960)** onto the workspace.

#### Step 2: Connect Devices
1. Choose the **Connections (lightning icon)**.
2. Use **Copper Straight-Through** cables to connect:
   - **PC0 → Switch (FastEthernet0/1)**
   - **PC1 → Switch (FastEthernet0/2)**

#### Step 3: Configure IP Addresses
1. Click on **PC0** > **Desktop** > **IP Configuration**
   - IP Address: `192.168.1.10`
   - Subnet Mask: `255.255.255.0`
2. Do the same for **PC1**:
   - IP Address: `192.168.1.11`
   - Subnet Mask: `255.255.255.0`

#### Step 4: Test Connectivity
1. Go to **PC0** > **Desktop** > **Command Prompt**
2. Type: `ping 192.168.1.11`
3. You should see `Reply from 192.168.1.11...` indicating successful communication.

---

## 🧠 3. What You Learned

✅ How to:
- Install Packet Tracer  
- Add and connect devices  
- Configure IP addresses  
- Test network connectivity  

---

## 🚀 Next Steps

Ready for more? Try adding:
- A **router** and configure interfaces  
- **DHCP settings** for automatic IP  
- **VLANs** and inter-VLAN routing  

---

## 🗂️ Repository Structure Suggestion

You can organize your GitHub repo like this:

