# Sope Power Tools: Katalon Automation

## General Usage 

1. Download & extract the sope-powertools from github.
2. Install & open the [Katalon Recorder Chome Extension](https://chrome.google.com/webstore/detail/katalon-recorder-selenium/ljdobmomdgdljniojadhoplhkpialdid).
3. Add the `Sope Powertools Automation Suite.html` file to Katalon, by clicking the 'folder' icon in the extension window, and selecting the file.
4. Select the automation (or 'test case') you want to run.
5. Follow instructions for that test case: 

## Set PowerApps Props

Note: There's a video [here](https://www.youtube.com/watch?v=LwADIPiLYK4) giving a quick tour of how this works. 

1. Open the PowerApps form in the same browser window Katalon is open for.
2. Set up the `csv` files you need (samples may be found in the folder 'set-powerapps-props'). Try not to unnecessarily set properties.
3. Import those `csv` files to the 'Data Driven' tab in Katalon.
4. Ensure the loadVars command is refering to the correct `csv` file.
5. Select the element you wish to automate, then hit 'Play'.
6. Observe the properties being set. Don't interact with the browser until all set. 

#### Troubleshooting 

- If on a slower computer, you may find that you need to increase the delayTime beyond 250ms.
- It's possible that the selectors are no longer valid. Contact @alirobe on github or twitter if this happens.