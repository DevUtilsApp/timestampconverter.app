UNIX Timestamp Converter
========================

Convert UNIX Timestamp to a human-friendly format without online tools. [DevUtils.app](https://devutils.app) allows you to quickly turn a UNIX Timestamp into a human-friendly format. You can also inspect more information from the datetime like relative time (e.g., xx minutes ago), ISO formatted string, or check the current date of the week, week of the year, etc...

<p align="center">
  <img src="https://devutils.app/assets/demo-unix-dark.png" alt="DevUtils.app: Unix Timestamp Converter macOS app"/>
  <br/>
  <a href="https://devutils.app/">🚀  Download</a> | <a href="https://devutils.app/demo">🎬  Demo & Screenshots</a> | <a href="https://github.com/DevUtilsApp/DevUtils-app">📝  View source</a>
</p>

Convert UNIX timestamp
----------------------

You can convert timestamps from anywhere in your macOS (terminal, in email, web browser,...). Activate the app by:

* Copy text ► Press ⌃⌥⌘Space `(Or your own customized hotkey, up to you)`
* Copy text ► Click to icon <img src="https://devutils.app/menu-icon-dark.png" alt="DevUtils.app status bar icon" width="28px" /> in the status bar
* Select text ► Right-click ► "Inspect in DevUtils.app" `(This menu appears after you install the app)`

Input
-----

Unix Time Converter received one input. The input can be in the following format:

*   Standard UNIX timestamp (seconds since epoch).
*   Milliseconds since epoch.
*   ISO date format.
*   The tool also tries to parse the input using popular formats like `yyyy/mm/dd` when possible.

You can also use the "Now" button to set the current timestamp, which is very convenient when you need to grab the current timestamp as a string.

Output
------

If the input is valid, the following information will be returned in the output:

*   The datetime rendered as local time in human-friendly format.
*   The datetime in ISO 8601 format.
*   The relative time compares to the current time (e.g., 3sec ago).
*   The UNIX time format: for when the input is in ISO format.
*   Day of the year.
*   Week of the year.
*   Whether the year is a leap year or not.

Options
-------

When you activate the app, DevUtils will inspect your clipboard content and automatically select the UNIX Timestamp Converter if the content is a valid UNIX Timestamp that falls within a certain range.

![DevUtils.app: Unix Timestamp Converter macOS app](https://devutils.app/assets/settings/setting-unix-time-converter.png)

By default, the range is `946684799-32503593600`, corresponding to the first second of the year 2000 to the last second of the year 3000. You can configure this to your own value if you prefer to.
