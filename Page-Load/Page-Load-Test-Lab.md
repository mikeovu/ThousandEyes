# Scheduling a Page Load Web Test

## Web Layer - Page Load Tests

<a href = "https://docs.thousandeyes.com/product-documentation/tests">ThousandEyes Tests</a>

<a href = "https://docs.thousandeyes.com/product-documentation/browser-synthetics/navigating-waterfall-charts-for-page-load-and-transaction-tests"> Navigating Waterfall Charts Documentation</a>

Page load tests use **te-chromium**, a browser based upon the Chromium browser codebase, to obtain in-browser site performance metrics. The metrics include the completed page load time and phase information for each DOM component.

## Schedule a Page Load Test

1. Navigate to https://app.thousandeyes.com

2. Navigate to `Cloud & Enterprise Agents > Test Settings`

<img src="test-settings.png">

3. In the `New Test` Settings, select the `Web` Layer, `Page Load` Test Type and configure any name and description you want.

<img src="add-test.png">

4. On the top right hand corner, you will see the `Views Enabled for This Test` box to review the test parameters.

<img src="test-parameters.png">

5. In the `Basic Configuration` section, enter `https://www.cisco.com` in the URL field. 

<img src="basic-configuration.png">

6. From the `Agents` drop-down menu, we will select five Cloud Agents

<img src="select-agents.png">


7. Leave all settings as default and click `Run Once`

<img src="five-agents-run.png">

8. A new browser tab will open and display the page load test. Verify the test was successful by observing the `Page Load Time` parameter. 

<img src="page-load.png">

<img src="page-load-map.png">

9. Go back to the other tab with the test settings and set the interval to 5 minutes. Click `Create New Test` to schedule the test. 

<img src="five-minute-basic.png">

10. Navigate to `Cloud & Enterprise Agents > Views` to view the test report.

<img src="views.png">

<img src="page-load-save.png">