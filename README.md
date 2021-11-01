# Writing Repository Boilerplate (Python Version)

## About

Download this repository.

Rename repository.

```sh
$ brew install pandoc
$ python3 -m venv venv
$ . venv/bin/activate
$ pip install -r requirements.txt
$ sh app.sh
```

Write your contents to src directory.

When you save, app.sh merge and build epub to dist directory.

## Customize

Replace `cover.png` your own 512*800 png file to covering book.

Add CSS to `style.css` to styling text.

( Now, [Water.css](https://watercss.kognise.dev/) and Google Fonts is importing. )
