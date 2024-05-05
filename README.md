markdown
Copy code
# OutpassApp

This repository contains a simple capacitor app created for the Outpass App.

## Usage

To get started, clone this repository:

git clone https://github.com/Vinishaa-ramesh/OutpassApp.git

css
Copy code

Navigate to the project directory:

cd Outpass-App

mathematica
Copy code

Install dependencies:

npm install

yaml
Copy code

Build the Ionic app:

ionic build

css
Copy code

### Viewing in Browser

To view the app in a browser, run:

ionic serve

python
Copy code

### Opening in Android

To open the app in an Android emulator or device, sync the project with Capacitor and then open the Android project:

npx cap sync android
npx cap open android

bash
Copy code

### Live Reload

To enable live reload functionality, run the following command with the `--external` flag:

ionic serve --external

perl
Copy code

Copy the external link provided and paste it into the `server.url` field in the `capacitor.config.ts` file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.