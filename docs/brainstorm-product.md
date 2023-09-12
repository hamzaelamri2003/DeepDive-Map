De inviduele brainstormen samengebracht en ingedeeld samen met de bestaande wensen in een; must have, should have, en could have indeling.

Must have:

1. **Incident Tracking System**: As a centerpiece of your application, implement a custom map using leaflet.js to showcase real-time updates about incidents.

   Each incident should be displayed as a distinctive marker on the map, and a click on it should reveal vital details like incident type, severity level, and nearest point of interest.

2. **Incident Claim System**: To promote coordination among crew members, the application should allow a crew to 'claim' an incident. Once an incident is claimed, it should be indicated on the map, signaling other crews that the incident is being addressed.
3. **Incident Management Workflow**: Implement specific logic within your application to ensure proper incident reporting flow.
   - The status of every incident should initially be set as 'Unclaimed.'
   - Once a crew member claims an incident, its status should change to 'Claimed.'
   - When the crew member reaches the incident location, they should be able to update the incident status to 'In Progress.'
   - After addressing the issue, the status should finally be changed to 'Resolved.'
4. **Incident Report Filing**: Upon resolution, the crew should be able to submit a detailed report about the incident through the application. The report should carry information about the incident, how it was addressed, the time taken for resolution, and issues encountered during the process. This information will help generate informative analytics.
5. **View and Filter Options**: It should offer users the ability to filter and sort incidents based on their status i.e., unclaimed, claimed, and resolved. Also, allow the crews to view only their claimed incidents for better individual task management.
6. **User-Friendly Interface**: Keeping our end-users in mind, the application should be designed to be intuitive, easy to navigate and operate -- even for the least tech-savvy among the cleaning crews.
7. **Responsiveness**: The application should be responsive, automatically adjusting the layout depending on the screen size and orientation. The hovercrafts come equipped with data terminals of varying sizes, and the crews should be able to use the application efficiently on all of them.

Should have:

- Nieuwe pagina: Lijst overview alle opdrachten

- Nieuwe pagina: Meer info

Could have:

- It is possible to Claim areas to prevent multipe clreaning crews from going to the same place.
- The app will advise the closest unclaimed and uncleaned area to make selecting where to go next easier.
- An area needs to be completly cleaned to be able to claim the next spot.
