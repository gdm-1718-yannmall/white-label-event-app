# white-label-event-app
---------
The white label event app is an open source React Native app by [In The Pocket](https://inthepocket.mobi).

## How to contribute
---------
We have a backlog of features documented in the [Projects](https://github.com/inthepocket/white-label-event-app/projects/) tab of this repository, if you want to contribute, you can drag an issue into the progress column.

We use *Git Flow*. Feature branches are branched from Develop, please use following naming convention for new branches:
`feature/[issueNmbr]-[issue_title_snake_cased]` i.e. `feature/123-write_great_code`.

When you completed an issue, you can open a pull request to develop.

## Get Started
---------
 * Clone this repository: `git clone https://github.com/inthepocket/white-label-event-app.git`
 * cd into folder: `cd white-label-event-app`
 * Install dependencies `npm install`
 * Run project `npm start`


## Setup & Hook a firebase database
---------

	* [go to https://console.firebase.google.com](https://console.firebase.google.com)
	* Add a Project (for web) (f.e.: white-label-event-app)
  * Change Database read/write rules --DEV MODE ONLY--

  ```json
  {
    "rules": {
      ".read": true,
      ".write": true
    }
  }
  ```  

	* Edit `/utils/firebaseConfig.json` with your own config.
