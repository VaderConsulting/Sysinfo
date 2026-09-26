# Sysinfo

VB6 system-info experiment shell (`Sysinfo.vbp`): a form that hosts the System Monitor OCX plus Task Scheduler, Winsock, directory-walk, document-properties, popup, and disk-management ActiveX controls, with a timer-driven label, for server and sysinfo UI experiments. Open `Sysinfo.vbp` in the VB6 IDE (needs those OCXs registered).

**Source last updated:** 2000-11-25 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Sysinfo.vbp`) | VB6 | WinForms exe | System Monitor / OCX sysinfo host form |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Sysinfo.vbp`

## Requirements

- Visual Basic 6.0 IDE
- ActiveX controls referenced by the project: sysmon.ocx, tasksched.ocx, cswsk32.ocx, dirwalk2.ocx, docprop2.dll, Popup.ocx, VCMAXB.OCX, dmview.ocx

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Sysinfo`. Project company field: Chips, Bits and Bytes.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
