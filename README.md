# GEXT

## What's GEXT?

GEXT is a very useful platform that will allow you to generate presentations with superpowers!
It helps companies and users to generate final and sharable documents from templates.

### How to use GEXT?

1. Log in to Gext with your Google account and select the template.
2. Select your template from your Drive account or choose one from your computer.
3. You already have in your hands the superpower: the fields of the presentation that you have "gexted" will automatically appear and you will be able to fill them in order to automatically generate a new copy.
4. Congratulations! Your presentation is ready! Now, you can take a look or download it. And remember:
"With great power comes great responsibility".

### How do I create a template in order to use it with GEXT?

To get all the superpowers from Gext presentations, in your template:

1. Write between two curly braces the text fields that you want to change...
2. or between three curly braces the images that you want to insert.

For example: {{name}} {{{image}}}


### How it works?

Once you have selected a template, this wonderful application will search all given keywords (following the previous said nomenclature) and autogenerate a useful form where you can change those keywords and images to whatever you need. Finally, you will be redirected to a final page where you can view your document in Drive or download it directly to your computer (in pptx or pdf format).

## How does the repository works?
This project has been created with [React](https://reactjs.org/), use [Material Design UI](https://material-ui.com/), depends on [Google Drive API](https://developers.google.com/drive/api/v3/about-sdk?hl=ru) and specifically the [Google Slides API](https://developers.google.com/slides/).

If you are thinking about forking or cloning this project to use it in your local, please be aware that you will need a *developer key*. Google has already a very useful [tutorial](https://developers.google.com/slides/quickstart/javascript) on how to get its *API Keys* and start working on.

Please, be very careful not to push your credential on a public platform (like Github). In order to prevent that, we have set several *.env* extensions on the *.gitignore* file and used the *.env.development.local* file to storage our *developer key*. In this *.env* file you should type the following code:

```
REACT_APP_API_KEY=YOUR_API_KEY
```

…where YOUR_API_KEY must be changed by your actual key.

If you prefer to use a value set outside of the project, instead of change YOUR_API_KEY by your key you should declare the variable in your shell and refer it on the *.env* file like:

```
REACT_APP_API_KEY=${NAME_OF_YOUR_VARIABLE}
```

Hope it helps you to run our project.


### Credentials through environmental variables

## How to improve Gext?
If you find any bug or you have any improvement suggestion, please send us an issue or a pull request. Thank you!

## GEXT team
[Laura Sánchez](https://github.com/babelarr)
[Roxana Sánchez](https://github.com/roxsb)
[Yen Hoang](https://github.com/japocoinyenhoang)
[Alba López](https://github.com/albahniuk)
[Silvia García](https://github.com/garcaplay)
