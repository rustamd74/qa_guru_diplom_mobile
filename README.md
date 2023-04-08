## The project of mobile autotests was implemented for the Wikipedia application
### Technologies used
<p  align="center">
<code><img width="5%" title="Python" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Python.svg/1024px-Python.svg.png"></code>
<code><img width="5%" title="Pycharm" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/PyCharm_Icon.svg/1200px-PyCharm_Icon.svg.png"></code>
<code><img width="5%" title="Pytest" src="https://upload.wikimedia.org/wikipedia/commons/b/ba/Pytest_logo.svg"></code>
<code><img width="5%" title="Selene" src="https://fs.getcourse.ru/fileservice/file/download/a/159627/sc/264/h/e0cabcb69a2df1e6b1086292c020a4a7.png"></code>
<code><img width="5%" title="Allure Report" src="https://avatars.githubusercontent.com/u/5879127?s=200&v=4"></code>
<code><img width="5%" title="Allure TestOps" src="https://marketplace-cdn.atlassian.com/files/92e2d8c3-2a30-46c0-bf21-2453a4a270d3?fileType=image&mode=full-fit"></code>
<code><img width="5%" title="Jenkins" src="https://avatars.githubusercontent.com/u/2520748?v=4"></code>
<code><img width="5%" title="Appium" src="https://cdn.worldvectorlogo.com/logos/appium.svg"></code>
<code><img width="5%" title="Browserstack" src="https://brandeps.com/logo-download/B/BrowserStack-logo-vector-01.svg"></code>
<code><img width="5%" title="GitHub" src="https://cdn-icons-png.flaticon.com/512/25/25231.png"></code>
<code><img width="5%" title="Telegram" src="https://cdn.icon-icons.com/icons2/923/PNG/256/telegram_icon-icons.com_72055.png"></code>
<code><img width="5%" title="Jira" src="https://seeklogo.com/images/J/jira-logo-C71F8C0324-seeklogo.com.png"></code>
</p>
<br> 

### Что проверяют тесты
* Search
* Language changes
<br>

### Ability to run tests on different environments:
* remote test bench
* real devices
* emulators 

### <img width="3%" title="Jenkins" src="https://avatars.githubusercontent.com/u/2520748?v=4"> [Starting a project in Jenkins](https://jenkins.autotests.cloud/user/oksana/builds)
##### Clicking on "Build Now" will start building tests and running them on the server Jenkins.
![Jenkins_run](/images/screenshots/jenkins.png)

### <img width="3%" title="Browserstack" src="https://brandeps.com/logo-download/B/BrowserStack-logo-vector-01.svg"> Starting a project in Browserstack
##### After starting the build in Jenkins, the tests begin to pass remotely through the Browserstack. Where in real time you can monitor the passage of the test throughз логи.

![Browserstack](images/screenshots/browserstack.png)

#### Video of passing tests on

![Browserstack](images/screenshots/bstack_test_video.gif)

### <img width="3%" title="Allure Report" src="https://avatars.githubusercontent.com/u/5879127?s=200&v=4"> Allure report
##### Based on the results of passing the tests, an Allure report is generated.
![Overview](/images/screenshots/report.png)

##### The Behaviors tab contains collected test cases, which describe the steps. Attachments are implemented for api methods. For combined tests, at the end of the test, a screenshot is taken and a video recording of the test is saved.
![Behaviors](/images/screenshots/behaviors.png)
![Suites](/images/screenshots/suites.png)

##### Video passing the test.
![This is an image](/images/screenshots/video.gif)

#### You can view the test logs on browserstack.:
![This is an image](/images/screenshots/bs_logs.png)
##### Implemented integration with Allure TestOps and Jira.
![Jira](/images/screenshots/jira.png)


### <img width="3%" title="Telegram" src="https://cdn.icon-icons.com/icons2/923/PNG/256/telegram_icon-icons.com_72055.png"> Integration with Telegram
##### At the end of the tests, send a mini report to telegram

![Telegram](/images/screenshots/telegram.png)
