# Since Last Incident

Would you like to track your or your team's production robustness? Set up your own 'Since Last Incident' page and watch!

## Installation

Let the `incident.html` file be available to a browser.

## Setup

1. Open the `incident.html` file in your favorite text editor.
2. Find the beginning of configuration (see the snippet below).

```javascript
// Zenith day threshold values:
// * Include day time only: 90 + 50.0 / 60.0
// * Include civil twilight: 96
// * Include nautical twilight: 102
// * Include astronomical twilight: 108
const zenithDayThresholdDegrees = 90 + 50.0 / 60.0;

// Put your city coordinates here
const latitude = 0.0;
const longitude = 0.0;

// Put last incident data here
const lastIncidentDate = new Date('1970-01-01T00:00:00Z');
const bestPeriodBegin = new Date('1970-01-01T00:00:00Z');
const bestPeriodEnd = new Date('1970-01-01T00:00:00Z');

// Easter eggs
const foolDayOn = false;
const newYearOn = false;
```
3. Amend the configuration and save the file.
4. Navigate your browser to `incident.html`'s URL.
  
