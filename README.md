# D-Alert
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
## A flutter application for Driver’s Drowsiness Detection.
- D-Alert is an app which requires camera to operate. 
- It can be used to detect drowsiness and alert the driver. 

## Screenshots
![D-Alert](https://drive.google.com/uc?export=view&id=1NA_KXmzcgo-Xvg4c9usBHJUEI4IOR_hV)


## Features

- Alerts Driver(Alarm)
- SMS alert to Emergency contact/ Concerned Authority
- Suggests nearby rest stations/gas stations.
- Repeated ignorance to alarm leads to revealing of location to nearby control room.

## Tech

D-Alert uses a tflite model extracted from training using MRL dataset and custom dataset to do its tasks such as detecting level of alertness/drowsiness from the live video captured from mobile camera.

## Installation
 To run this project locally you must have flutter installed.

$ flutter pub get
start debugging the main.dart file

If this doesn't work try removig 'pubspec.lock' file and run 'flutter pub get'
## External dependencies

- Google Map API
- Twilio SMS Service

## Development

Want to contribute? Great!

Make a change in your file and make a Pull request.


## Tech Stack

**Client:** Flutter

**Server:** Firebase


## Environment Variables

To run this project, you will need to add the following environment variables.

`API_KEY`

## Authors

- [@arjunr50](https://github.com/arjunr50)
- [@Allenvt](https://github.com/Allenvt)
- [@Indulekha603](https://github.com/Indulekha603)
- 



## Feedback

If you have any feedback, please reach out to us at arjunr2022@cs.ajce.in


## License

[MIT](https://choosealicense.com/licenses/mit/)

