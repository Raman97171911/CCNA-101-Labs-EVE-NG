# Lab Setup – EVE-NG for the CCNA 101 Labs

Everything you need to run the labs in this repository.

## 1. EVE-NG Community Edition

- Official download: https://www.eve-ng.net/index.php/download/
- Install on VMware Workstation: 4+ CPU (VT-x/AMD-V enabled), 8–16 GB RAM, 100 GB disk.
- Web login after install: `admin` / `eve`.

## 2. Free setup kit (Google Drive)

EVE-NG CE installer + open-source Linux images (Ubuntu 24.04, Slax, OpenMediaVault), with install steps and checksums:

👉 **<GOOGLE-DRIVE-LINK>**

## 3. Images used by the labs

| Role | Image name in the .unl files | EVE-NG path |
|------|------------------------------|-------------|
| Switch | `i86bi_linux_l2-adventerprisek9-ms.SSA.high_iron_20190423.bin` | `/opt/unetlab/addons/iol/bin/` |
| Router | `i86bi_linux_l3-adventerprisek9-ms.154-2.T4.bin` | `/opt/unetlab/addons/iol/bin/` |
| PC | VPCS (built into EVE-NG) | – |

> Cisco images are **not** provided here. Get them legally, e.g. from **Cisco Modeling Labs (CML-Free)**.
> If your image file name is different, edit the node in EVE-NG and pick your image.

After copying images:
```bash
/opt/unetlab/wrappers/unl_wrapper -a fixpermissions
```

## 4. Import a lab

1. Download the lab `.unl` file from its folder.
2. Copy it to `/opt/unetlab/labs/` on the EVE-NG server.
3. Run `fixpermissions` (above) and refresh the EVE-NG web UI.
