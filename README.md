# scoop-torlek

Scoop bucket for [Torlek](https://github.com/Androlax2/agent-cockpit): a Windows launcher for the Linux Torlek inside WSL 2.

```powershell
scoop bucket add torlek https://github.com/Androlax2/scoop-torlek
scoop install torlek/torlek
```

The manifest is rendered from each release's `SHA256SUMS` by `packaging/windows/render.py` in the main repository. See [the packaging page](https://github.com/Androlax2/agent-cockpit/blob/main/docs/packaging/windows.md).
