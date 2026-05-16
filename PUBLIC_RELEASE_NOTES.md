# Public Release Notes

The laptop-test EXE is built and works as a private one-click tester, but it embeds binary theme/system assets:

- `Assets/TahoeTraffic.theme`
- `Assets/TahoeTraffic.msstyles`
- `Assets/ApplicationFrame.dll.patched`

Do not push those assets or the private EXE to a public repository unless redistribution rights are cleared.

For a public release, replace the embedded assets with:

- Original/open-license Tahoe-style button assets, or
- A runtime patcher that generates the required resources from user-provided/local files.

The app already includes the correct UX:

- `Tahoe style close/minimize/maximize`
- `Old Windows close/minimize/maximize`

Backups are written to:

```text
C:\ProgramData\JhonLloydMolino\TahoeTitlebar\Backups
```
