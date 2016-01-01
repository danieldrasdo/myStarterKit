# myStarterKit

[myStarterKit](https://github.com/danieldrasdo/myStarterKit) is used in setting up my local developing environment.

**Prior to using [myStarterKit](https://github.com/danieldrasdo/myStarterKit), make sure Node.js version 4.2.3 or higher is installed. You can check the Node.js version you have installed by running the following command in your terminal.**

	node -v

##Install Packages

After cloning [myStarterKit](https://github.com/danieldrasdo/myStarterKit) to your computer, `Terminal` into your project directory and run the following command to install all required node packages.\*

	npm install

\* *You may need to use `sudo npm install`. Also, it may take a bit to install the devDependencies.*

##Start

While still in your project directory, run the following command:

	gulp

If that doesn't work, chances are you don't have gulp installed globally, which gives you the availability of using `gulp` on the command line. Try using the following command to install gulp globally:

	npm install -g gulp

Then try running `gulp` again.


####Notes

1. Open the project folder in your IDE.
2. The sass/js files within the `_src` directory are the files used while developing.
3. Open `index.html` and update the `title`.
4. Both the `assets/` directory and `index.html` are used in production.
5. If you'd like, you could use Bower to grab the latest versions of jQuery, Angular, etc., but I personally like fetching those and linking them up in my html myself.
