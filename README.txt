working on https://www.obeythetestinggoat.com/pages/book.html#toc

- downloading/installing geckodriver:
use curl to avoid mac issues.
cd ~/Applications/
curl https://github.com/mozilla/geckodriver/releases/download/v0.26.0/geckodriver-v0.26.0-macos.tar.gz
gives redirect, so use -L flag.


set up python virtualenv using virtalenvwrapper:
cd projects/learning/tdd_python
mkvirtualenv tdd
workon tdd
# install django and selenium
pip install "django<1.12" "selenium<4"
deactivate

