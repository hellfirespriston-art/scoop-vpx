# scoop-vpx

A [Scoop](https://scoop.sh) bucket for **VPX** — a Windows desktop music player with a
per-track demoscene oscilloscope, playing around 70 formats including the MOD/XM/IT/S3M
tracker modules of the 90s.

[![VPX oscilloscope in motion](https://vpx-landing.vercel.app/vpx-osc.gif)](https://vpx-landing.vercel.app)

```
scoop bucket add vpx https://github.com/hellfirespriston-art/scoop-vpx
scoop install vpx
```

The installer is Inno Setup, per-user (`PrivilegesRequired=lowest`) — no administrator
prompt, nothing else installed on the machine. Scoop extracts it with `innounp`.

- Homepage and download: https://vpx-landing.vercel.app
- Try the engine in the browser, no install: https://vpx-scope.vercel.app/en/
- Releases: https://github.com/hellfirespriston-art/vpx-releases

VPX is proprietary software with a 3-day free trial and a one-off licence. This bucket
only points at the official installer published in the releases repository above.
