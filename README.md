# TEST I18N

This is the task from the "Testing" course. You should check if the language switcher exists:

* Clone the project. For example:

`git clone git@github.com:Ann-90/test_i18n.git`

* Enter the root directory of the project

`cd test_i18n`

* In the root directory create the environment

`python3 -m venv env_name`

`env_name/bin/activate`

`pip install -r requirements.txt`

* Run the test project. Replace the `language` variable with your local (for example: `en` or `es`)

`pytest --language={language} test_items.py -s -v`

* Don't forget to drink your tea 
