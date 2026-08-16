# scoop-vpx

A [Scoop](https://scoop.sh) bucket for **VPX** — a Windows desktop music player with a
per-track demoscene oscilloscope, playing around 70 formats including the MOD/XM/IT/S3M
tracker modules of the 90s.

[![VPX oscilloscope in motion](https://vpx-landing.vercel.app/vpx-osc.gif)](https://vpx-landing.vercel.app)

```
scoop bucket add vpx https://github.com/hellfirespriston-art/scoop-vpx
scoop install vpx-player
```

The app is named `vpx-player`, not `vpx`: the short name is already taken by Visual Pinball X
in several buckets, and installing that instead would be a bad surprise. If you have other
buckets added, `scoop install vpx/vpx-player` removes any ambiguity.

The installer is Inno Setup, per-user (`PrivilegesRequired=lowest`) — no administrator
prompt, nothing else installed on the machine. Scoop extracts it with `innounp`.

- Homepage and download: https://vpx-landing.vercel.app
- Try the engine in the browser, no install: https://vpx-scope.vercel.app/en/
- Releases: https://github.com/hellfirespriston-art/vpx-releases

The manifest is kept up to date automatically: an Excavator workflow checks the releases
repository every 6 hours and bumps version, URL and hash on its own.

VPX is proprietary software with a 3-day free trial and a one-off licence. This bucket
only points at the official installer published in the releases repository above.
