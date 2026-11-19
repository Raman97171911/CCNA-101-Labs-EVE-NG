# CCNA 101 Labs on EVE-NG

Ready-to-use **EVE-NG lab files (.unl)** for CCNA practice. One lab per day, 101 days.

Every lab is self-contained. The topology, objective, tasks, solution, verification commands and the real device output are all drawn on the EVE-NG canvas, so you can open the lab and start practising immediately.

![Platform](https://img.shields.io/badge/Platform-EVE--NG-1E3A5F)
![Track](https://img.shields.io/badge/Track-CCNA-185FA5)
![Progress](https://img.shields.io/badge/Labs-3%20%2F%20101-3B6D11)

---

## Lab index

| # | Lab | Topic | Folder |
|---|-----|-------|--------|
| 001 | Configuring Standard VLANs on Catalyst Switches | VLANs, access ports | [LAB-001-Standard-VLANs](LAB-001-Standard-VLANs/) |
| 002 | Configuring Extended VLANs on Catalyst Switches | Extended VLANs, VTP transparent | [LAB-002-Extended-VLANs](LAB-002-Extended-VLANs/) |
| 003 | Configuring VTP Clients and Servers on Catalyst Switches | VTP server/client, 802.1Q trunk | [LAB-003-VTP-Server-Client](LAB-003-VTP-Server-Client/) |
| 004 | _coming soon_ | | |

> A new lab is added every day. Follow along on [LinkedIn](https://www.linkedin.com/in/raman9717).

---

> 🛠️ **New to EVE-NG?** Start with the [Lab Setup guide](SETUP.md): EVE-NG install, free Linux images and the Cisco images these labs use.

## How to import a lab into EVE-NG

1. Download the `.unl` file from the lab folder.
2. Copy it to your EVE-NG server, for example with MobaXterm SFTP or WinSCP:
   ```
   /opt/unetlab/labs/
   ```
3. Fix permissions on the EVE-NG server:
   ```bash
   /opt/unetlab/wrappers/unl_wrapper -a fixpermissions
   ```
4. Refresh the EVE-NG web UI and open the lab.

---

## Requirements

| Item | Used in these labs |
|------|--------------------|
| EVE-NG | Community Edition |
| Switch image | Cisco IOL L2 (`i86bi_linux_l2-adventerprisek9-ms`) 15.2 |
| Router image | Cisco IOL L3 (where needed) |
| PCs | VPCS (where needed) |

> Cisco images are **not** included in this repository. Use your own licensed images.

---

## Canvas layout (same in every lab)

| Box | What it contains |
|-----|------------------|
| Title (navy) | Lab number and name |
| Objective (blue) | What you will learn |
| Tasks (amber) | Step-by-step tasks |
| Solution (black) | Commands, grouped by task (try first, then check) |
| Verify / Output (green) | Show commands and real output |
| Key Points / Common Mistakes | Concepts and typical errors |

The template and its colour guide are in [LAB-000-Template](LAB-000-Template/).

---

## Credits

Lab scenarios are based on **101 Labs for the Cisco CCNA Exam** by Paul Browning and Farai Tafa.
The EVE-NG topologies, canvas design, solutions and device outputs in this repository are my own work.

## Author

**Raman Kumar Shakya** · [GitHub](https://github.com/Raman97171911) · [LinkedIn](https://www.linkedin.com/in/raman9717)
