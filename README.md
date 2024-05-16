# onboarding repack example

How to run repack:
```
bun install
npx eas-cli@latest update:configure

# for iOS device (ad-hoc) repack
npx eas-cli@latest build -p ios -e development --repack

# for iOS simulator repack
npx eas-cli@latest build -p ios -e development-simulator --repack

# for Android repack
npx eas-cli@latest build -p android -e development --repack
```
