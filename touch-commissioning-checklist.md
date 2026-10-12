# External Windows Touch Display Commissioning Checklist
Use this checklist when the documented configuration sends video from an external Windows PC over HDMI and returns touch input over USB. Confirm the display model and connection points before testing. A working picture alone does not establish a working touch path.
MWE's [Help Center](https://www.mwedisplay.com/pages/help-center) describes this arrangement for supported touch models. Its [wall-mount touchscreen product page](https://www.mwedisplay.com/it/products/mwe-wall-mount-touchscreen-digital-signage) also describes HDMI with USB touch control. Other configurations can use different connections.
## Record the configuration
| Item | Record |
| --- | --- |
| Display model and serial label | |
| Built-in system or external Windows PC | |
| PC model and Windows version | |
| Video connection, adapters and display input | |
| USB touch connection and any hub | |
| Desktop mode: duplicate or extend | |
| Target application and version | |
| Test date and installer | |
## Test the two paths separately
1. Confirm the selected display input matches the PC's video connection.
2. Check that the expected picture appears and stays present while the target application runs.
3. Connect the documented USB touch cable to the correct PC and display connection points.
4. Check whether the PC recognizes the touch input device. Record what Windows actually shows rather than assuming a driver is missing.
5. Tap a known control in the target application. Test the center and edges of the screen.
6. With multiple displays, confirm that touching the intended screen controls the intended desktop. Record any offset or wrong-screen response.
7. Check application input behavior separately. A Windows desktop responding to touch does not prove that every application handles gestures correctly.
8. If restarting the PC or display is part of the operating plan, repeat the same checks after that restart.
The optional [local pointer event test](touch-input-test.html) reports the pointer events delivered to a browser page. Download it and open it locally on the connected PC. A `touch` event shows that the browser received a touch event; it does not certify display accuracy, multitouch specifications, application compatibility, or long-term reliability.
## Keep an acceptance record
| Check | Pass / fail / not tested | Evidence or open question |
| --- | --- | --- |
| Expected Windows picture | | |
| Picture remains present during the task | | |
| USB touch connection recognized | | |
| Touch reaches the intended desktop | | |
| Center and edge taps behave as expected | | |
| Target application accepts the required input | | |
| Behavior after planned restart | | |
| Next operator can identify both connections | | |
Label the video and touch-data cables, retain the tested configuration, and assign an owner to every unresolved item. For a failed check, collect the model label, connection photos, Windows version, target application version, and a short continuous recording of the symptom. Use the [MWE Help Center](https://www.mwedisplay.com/pages/help-center) for the matching support route.
Inspect external connections only. Follow the model's instructions and seek support before any internal inspection.
Reviewed against the linked public MWE sources on October 12, 2026. This is a commissioning aid, not a model-specific compatibility certificate.
