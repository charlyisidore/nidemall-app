# NideMall (mobile app)

Mobile app for [NideMall](https://github.com/charlyisidore/nidemall-server).

## Installation

```bash
yarn install
```

## Usage

```bash
yarn run dev
```

## Build

### Android

```bash
npx cap add android
cd android/
./gradlew buildRelease
```

Output is located in `android/app/build/outputs/apk/release/app-release-unsigned.apk`.

## License

[MIT](./LICENSE)
