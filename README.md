# Nergora Public Service

Nergora **.NET imza servisi** (Nergora.Imza.Service + Detacher) release'leri ve runtime feed'i.

- Release'ler: `service-v<surum>` etiketi; RID basina `nergora-service-<rid>-<surum>.zip`.
- Feed: `feed.json` — `{version, platforms: {rid: {path, sha256, size}}}`. Masaustu kabuk bu dosyayi okur ve zip'i SHA-256 dogrulayarak indirir.
- Bu repo YALNIZ servis icindir; masaustu uygulama release'leri `Nergora/public` tedir.
- Yukleme: `Nergora/desktop-signature-app` -> Actions -> "publish service" (PUBLIC_REPO_TOKEN ile).
