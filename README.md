# Kid Event Server

The event server has a centralized location for the management of events in a distribution environment.

The application is optimized for [Raspberry Pi](https://www.raspberrypi.org/)

## Flow description

The [Kid NFC](https://github.com/kairops/Kid-NFC), [Kid FingerPrint](https://github.com/kairops/Kid-FingerPrint) and [Kid FaceID](https://github.com/kairops/Kid-FaceID) projects shoots an events. This project receives and process the event, calling another services, as for example, [Kid-lock](https://github.com/kairops/Kid-Lock)

## Instalation

```console
npm install
```

## Run server

```console
npm start
```

Port is defined at [.env](src/.env) enviroment config file.

## Test

```console
npm test
```