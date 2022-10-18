# WhatsApp Clone with Tauri, NextJS, TailwindCSS

## Tech Stack

- NextJS
- Tauri
- TailwindCSS
- Ably - for Real time
- Figma Community - https://www.figma.com/community/file/1048915684687472577

## Local Development

Make sure you have cargo installed first <https://www.rust-lang.org/learn/get-started>

Install Dependencies

```bash
pnpm i
```

Run in Localhost

```bash
pnpm wa dev
```

Or run in App

```bash
pnpm wa tauri dev
```

## Build for Mac

[Read more for other different binary target](https://tauri.app/v1/guides/distribution/macos#binary-targets)

```bash
npx nx run whatsapp-clone-tauri-next:tauri build --target universal-apple-darwin
```
