# RemindMeWhenReady

## Description
A cross-platform mobile app aimed at resolving the mental anxiety coming from excessive technology use, by allowing users to customize the notifications coming from their phone and beyond!
Traditionally, the solution to this problem has been to avoid technology use but with the growing relevance of technology in our lives, this has become impractical.
RemindMeWhenReady uses an approach to allow users to select the sources of their most **important** notifications for an immediate response while retaining the old notifications for later viewing.

#### Our goal is to providers users with only the key information that they require, while ensuring that they are caught up with everything else.

## Setup & Installation

### Backend

Our backend consists of two Restful flask servers designed to support a web scraper and a web-sockets based notification service,
organized as a microservices architecture with Docker.

1. [Install Python](https://www.python.org/downloads/)

2. Navigate to either the ```/Back End``` or  ```/Web Scraper``` folder on the terminal

3. [Create and activate Python virtual environment](https://docs.python.org/3/library/venv.html)

4. Install pip requirements using the following command ```pip install -r requirements.txt```

5. Run flask server using the following command ```flask run```

### Flutter

1. Install Flutter for [Mac](https://flutter.dev/docs/get-started/install/macos), [Windows](https://flutter.dev/docs/get-started/install/windows) or [Linux](https://flutter.dev/docs/get-started/install/linux)

2. Open your code editor or IDE of choice. [Androd Studio](https://flutter.dev/docs/get-started/editor) works extremely well with Flutter 

3. Navigate to the `/flutter_app` folder

4. Ensure you have a compatable device connected 

5. If you are using a text editor, enter `flutter run` with the device connected to run the project 

6. If you are using Android Studio, instructions are [here](https://flutter.dev/docs/get-started/test-drive/#run-the-app) to run it 


## Todo

- Enable server-client communication for notifications by using web sockets with the aiohttp framework
