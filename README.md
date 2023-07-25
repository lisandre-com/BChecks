# BChecks
BChecks to use within Burp Suite.

## Create or import BChecks

* Click on the _Extensions->BChecks_ tab.
* Click on _New_ to create a new BCheck, or click on _Import_ to import a file.

## Run BChecks

* Click on the _Target->Site map_ tab.
* Right-click on the target host, and click _New scan_.
* Under _Scan details_, select _Audit selected items_.
* Under _Scan configuration_:
    * Click on _New_.
    * Enter configuration name “BChecks only”.
    * Under _Issues Reported_:
        * Select _Select individual issues_.
        * Click in the list, Ctrl-A, right-click and unselect _Enable_.
        * Click to select only _BCheck generated issue_.
        * Select _Save to library_ (for reuse) and click _Save_.
    * Click _OK_.
