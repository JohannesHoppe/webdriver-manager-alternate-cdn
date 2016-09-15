# webdriver-manager-alternate-cdn

Evil company proxy forces me to do this.
Yes, they blocked the original CDN:

- https://selenium-release.storage.googleapis.com/
- https://chromedriver.storage.googleapis.com/

### Protractor 3.1.1
Protractor 3 is compatible with nodejs v4 and newer.

```
npm install -g protractor@3.1.1
webdriver-manager update --alternate_cdn=http://johanneshoppe.github.io/webdriver-manager-alternate-cdn/
```

* [2.51/selenium-server-standalone-2.51.0.jar](https://selenium-release.storage.googleapis.com/2.51/selenium-server-standalone-2.51.0.jar) == [2.51/selenium-server-standalone-2.51.0.jar](http://johanneshoppe.github.io/webdriver-manager-alternate-cdn/2.51/selenium-server-standalone-2.51.0.jar)
* [2.21/chromedriver_win32.zip](https://chromedriver.storage.googleapis.com/2.21/chromedriver_win32.zip) == [2.21/chromedriver_win32.zip](http://johanneshoppe.github.io/webdriver-manager-alternate-cdn/2.21/chromedriver_win32.zip)


### Protractor 2.1.0
When using nodejs v0.12, use protractor 2!

```
npm install -g protractor@2.1.0
webdriver-manager update --alternate_cdn=http://johanneshoppe.github.io/webdriver-manager-alternate-cdn/
```

* [2.45/selenium-server-standalone-2.45.0.jar](https://selenium-release.storage.googleapis.com/2.45/selenium-server-standalone-2.45.0.jar) == [2.45/selenium-server-standalone-2.45.0.jar](http://johanneshoppe.github.io/webdriver-manager-alternate-cdn/2.45/selenium-server-standalone-2.45.0.jar)
* [2.15/chromedriver_win32.zip](https://chromedriver.storage.googleapis.com/2.15/chromedriver_win32.zip) == [2.15/chromedriver_win32.zip](http://johanneshoppe.github.io/webdriver-manager-alternate-cdn/2.15/chromedriver_win32.zip)
