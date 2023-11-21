# Garmin Ballistics
A widget for Garmin Fenix watches that calculate ballistic data

## Build
`monkeyc -d DEVICE_NAME -f monkey.jungle -o garmin_ballistics.prg -y developer_key.der`

## Simulate
`connectiq & monkeydo garmin_ballistics.prg DEVICE_NAME`
