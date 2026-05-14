# Canon Printer Error Codes — Complete Reference Guide

Every Canon Pixma printer communicates problems through error codes.
Knowing what each code means saves time and prevents unnecessary
repairs. This reference covers the most common Canon error codes,
what they actually indicate, and the fastest fix for each one.

---

## Paper and Feed Errors

### Error 1000 / E02 — No Paper Loaded

The printer attempted to feed paper and found none in the tray.

**Fix:** Load paper into the rear tray or front cassette. Align the
paper guides snugly against the paper edges. Press OK or Resume on
the printer panel to continue the print job.

---

### Error 1300 / E03 — Paper Jam

Paper is stuck somewhere in the feed path.

**Fix:** Open every access panel — front cover, rear access door,
output tray. Remove jammed paper slowly and steadily without tearing
it. A torn piece left inside causes the same error repeatedly. After
clearing, press OK to resume. If the error returns immediately,
use a flashlight to check for small torn fragments along the
roller path.

---

### Error 1000 Series — Paper Feed Failures

| Code | Meaning | Fix |
|------|---------|-----|
| 1001 | Paper jam in feed roller | Remove paper, clean rollers with damp cloth |
| 1002 | Paper jam in transport | Check rear access door for stuck paper |
| 1007 | Paper jam — multiple sheets fed | Fan paper before loading, reduce stack size |
| 1008 | Paper jam — paper too small | Use correct paper size for print job |

---

## Ink and Cartridge Errors

### Error E04 / E05 — Wrong or Missing Cartridge

The printer cannot detect a valid ink cartridge in one or both slots.

**Fix:** Open the cartridge bay. Remove each cartridge and reseat it
firmly until it clicks. If a cartridge was recently replaced, confirm
it is the correct model for your specific printer. Cartridge model
numbers vary even between similar Canon Pixma models.

---

### Error E13 / E16 / 1641 / 1642 — Ink Depleted

One or more cartridges has run out of ink.

**Fix:** Replace the empty cartridge. On most Canon Pixma models you
can press Stop/Reset once to temporarily continue printing with
depleted ink — this is not recommended as it risks print head damage
from heat buildup without ink acting as coolant.

---

### Error 1660 / E07 — Cartridge Not Installed Correctly

The cartridge is present but not properly seated.

**Fix:** Open the cartridge bay. Press the cartridge downward firmly
until you hear or feel a definite click. A cartridge that appears
inserted but is not fully locked causes this error consistently.

---

### Error 1680 / 1681 — Incompatible Cartridge Combination

The installed cartridges are not compatible with each other or with
this printer model.

**Fix:** Verify both cartridges are the correct model for your printer.
Canon printers reject cartridges designed for different regional
markets — a cartridge purchased outside the US or Canada may be
flagged as incompatible on North American printer models.

---

### Error 1682 / 1684 / 1689 — Cartridge Cannot Be Recognized

The printer detects a cartridge is installed but cannot read its
authentication chip.

**Fix:** Remove the cartridge and clean the gold contacts on its
underside using a dry lint-free cloth. Reinstall and test. If the
error persists, the cartridge chip may be damaged or the cartridge
is a counterfeit. Genuine Canon cartridges with intact chips resolve
this error consistently.

---

### Error 1686 / 1688 — Ink Has Run Out (Override Available)

Ink is fully depleted. The printer is requesting confirmation to
stop.

**Fix:** Replace the cartridge immediately. Pressing Stop/Reset to
override and continue printing on an empty cartridge causes print
head thermal damage over repeated use. This is not a recommended
workaround.

---

## Ink Absorber Errors

### Error P07 / 5B00 / 1700 / 1701 — Ink Absorber Full

The ink absorber pad — an internal sponge that collects overflow ink
from cleaning cycles — has reached capacity.

This is one of the most misunderstood Canon errors. The printer
tracks absorber usage through a software counter, not a physical
sensor. The counter triggers this error when it reaches a preset
threshold regardless of whether the physical pad is genuinely full.

**Fix — Software reset:** Use Canon's Service Tool to reset the waste
ink counter. Download the tool, connect the printer via USB, navigate
to the Main tab and clear the ink absorber counter. Power cycle
after resetting.

**Fix — Physical:** Replace the absorber pad and reset the counter.
Replacement pads are inexpensive and available for most Pixma models.
Resetting the counter without replacing the pad — or replacing the
pad without resetting the counter — both result in the error
returning.

---

### Error 1710 / 1711 — Ink Absorber Almost Full

Warning that the absorber counter is approaching its threshold.

**Fix:** Plan the absorber reset or replacement before the P07
error appears. Continuing to print without addressing this will
produce the full P07 error within a small number of print jobs.

---

## Print Head Errors

### Error 1401 / 1403 — Print Head Not Installed or Not Detected

The printer cannot communicate with the print head.

**Fix:** Open the cartridge bay and remove all cartridges. Locate the
print head locking lever — usually orange or grey — unlock it and
remove the print head. Clean the gold electrical contacts on the
print head underside using a lint-free cloth lightly dampened with
distilled water. Allow to dry completely. Reinstall the print head,
lock the lever, reinstall cartridges, and power on.

---

### Error E31 — Print Head Error (E-Series Models)

Same root cause as 1403 on models using E-series error codes. Print
head contacts are dirty or the print head is not fully locked.

**Fix:** Identical process to 1403 above. Contact cleaning resolves
this in the majority of cases.

---

### Error 5200 — Print Head Overheating

The print head temperature sensor detected overheating during
operation.

**Fix:** Power off the printer immediately. Leave it unplugged for
20 minutes to cool completely. Inspect the cartridges — an empty
cartridge causes the print head to fire without ink cooling the
nozzles, which triggers thermal shutdown. Replace any empty
cartridges before restarting. If the error recurs after cooling
and cartridge replacement, the print head may have sustained
thermal damage.

---

### Error 5100 — Carriage Error

The print head carriage cannot complete its movement cycle.

**Fix:** Power off and unplug. Open the cartridge access cover and
inspect the carriage rail for obstructions — paper fragments, debris,
or a cartridge that has partially dislodged. With the printer
unplugged, manually slide the carriage left and right to feel for
resistance. Remove any obstruction. Check the encoder strip — the
thin transparent strip running across the carriage path — for ink
smudging that might confuse the position sensor. Clean gently with
a dry lint-free cloth if smudged.

---

## Connectivity and Setup Errors

### Error 2001 / 2002 — WiFi Setup Failed

The printer attempted to connect to a wireless network and failed.

**Fix:** Verify your WiFi password is correct. Confirm the network
is broadcasting on 2.4GHz — Canon Pixma printers do not support
5GHz. If your router uses WPA3 security, switch to WPA2/WPA3 mixed
mode during setup. Restart both the router and printer before
retrying the WiFi setup process.

For a complete walkthrough of Canon WiFi setup including router
compatibility issues that commonly cause this error,
[how to set up canon printer on wifi](https://printersolved.com/ij-start-canon-setup/)
covers the full process for US and Canada users.

---

### Error 2700 / 2802 — Network Connection Error

The printer lost its network connection after a previously successful
setup.

**Fix:** Power cycle the printer and router. If the error recurs
after reconnecting, the router has likely reassigned the printer's
IP address. Log into your router admin panel and assign the printer
a static IP using its MAC address — visible on the network
configuration page printed by holding Stop/Reset for 5 seconds.

---

## Scanner Errors

### Error 2111 / 2113 — Scanner Error (Wireless Scan Failed)

The scanner cannot communicate with the host computer over the
wireless connection.

**Fix:** Confirm IJ Scan Utility is installed and running on your
computer. The scan function requires Canon's scan driver — not just
the basic print driver. If IJ Scan Utility is installed but the
printer does not appear as a scanner, uninstall all Canon software
and reinstall using the full driver package.

---

### Error 2500 — Calibration or Scanner Error

Typically appears after a firmware update or factory reset.

**Fix:** Run print head alignment from Settings → Maintenance →
Print Head Alignment. If the error persists, perform a factory reset
and complete the setup process from the beginning.

---

## Critical Hardware Errors

### Error 5011 / 5012 — Printer Error (Internal)

Internal hardware fault detected.

**Fix:** Power off, unplug for 5 minutes, reconnect and power on.
If the error persists through multiple restarts, the printer requires
service. These codes indicate an internal component failure beyond
user-level repair.

---

### Error 6000 / 6001 — Paper Jam (Rear Path)

Paper is jammed specifically in the rear feed path.

**Fix:** Open the rear access door. Remove jammed paper by pulling
it straight out without tearing. If the paper tears, retrieve all
fragments before closing the door. The rear path jam is most common
when printing on heavier paper stock or envelopes.

---

### Error 6830 / 6831 / 6832 / 6833 — Ink Absorber Full (Specific Models)

Variant of the P07 / 5B00 absorber error on certain Canon Pixma and
MegaTank models.

**Fix:** Identical to P07 resolution — reset the waste ink counter
using Canon's Service Tool and replace the absorber pad if it is
physically saturated.

---

## General Reset Procedure for Persistent Errors

When an error code persists through standard fixes, a factory reset
clears stored error states that survive power cycling:

1. Make sure the printer is powered on
2. Press and hold **Stop/Reset**
3. While holding, press and hold **Power**
4. Hold both for 5 seconds
5. Release **Stop/Reset** while keeping **Power** held
6. Press **Stop/Reset** twice
7. Press **Power** to confirm

The printer resets and restarts. After a factory reset, WiFi setup
and driver reinstallation are required before printing.

After any factory reset or major error resolution, the driver on
your connected computer may need to be reinstalled. [This guide](https://printersolved.com/ij-start-canon-setup/)
walks through the complete driver reinstallation process for Canon
printers in the US and Canada — including port configuration steps
that prevent offline errors from returning after the reset.

---

## Quick Reference Table — Most Common Error Codes

| Code | Category | Meaning | User Fixable |
|------|----------|---------|--------------|
| E02 / 1000 | Paper | No paper loaded | Yes |
| E03 / 1300 | Paper | Paper jam | Yes |
| E04 / E05 | Ink | Wrong or missing cartridge | Yes |
| E07 / 1660 | Ink | Cartridge not seated | Yes |
| E13 / 1641 | Ink | Ink depleted | Yes |
| E16 / 1688 | Ink | Ink depleted — override | Yes |
| E31 / 1403 | Print head | Head not detected | Usually |
| P07 / 5B00 | Absorber | Ink absorber full | Yes (with tool) |
| 5100 | Carriage | Carriage blocked | Usually |
| 5200 | Print head | Overheating | Usually |
| 5011 | Hardware | Internal fault | No — service needed |
| 2001 / 2002 | WiFi | Connection failed | Yes |
| 2802 | Network | Network dropped | Yes |

---

*This reference covers Canon Pixma models sold in the United States
and Canada. Error code behavior may vary slightly between firmware
versions and regional printer configurations.*
