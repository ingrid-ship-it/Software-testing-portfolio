# Bug Report: Geolocation "Snapping" Overrides Manual Address Entry

*App name: Uber Eats (Android)
*Severity: High (Impacts delivery accuracy)

#Summary
The app overrides a manually entered street address with a neighboring address based on GPS proximity.

#Steps to Reproduce
1. Open Uber Eats and enter a manual address.
2. Select the correct house number from the dropdown.
3. Observe the saved address in the profile.

#Expected Result

​The application should save and display the exact house number (No. 60) that I manually entered and selected.
The app should save the exact house number selected.

# Actual Result

​The application "snaps" the address to the neighbor's house number (No. 61) because the GPS pin is physically closer to that property.