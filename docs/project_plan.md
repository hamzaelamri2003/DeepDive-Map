# Plan van aanpak

### Purpose: Define the problem you're solving and the goals of your prototype.

De huidige map heeft te weinig interactie. Hiervool willen we meerdere functies toevoegen voor een betere evaring.

### Scope: Detail what your prototype will and won't do.

- **Incident Tracking System**: As a centerpiece of your application, implement a custom map using leaflet.js to showcase real-time updates about incidents.
  Each incident should be displayed as a distinctive marker on the map, and a click on it should reveal vital details like incident type, severity level, and nearest point of interest.
- **Incident Claim System**: To promote coordination among crew members, the application should allow a crew to 'claim' an incident. Once an incident is claimed, it should be indicated on the map, signaling other crews that the incident is being addressed.
- **Incident Management Workflow**: Implement specific logic within your application to ensure proper incident reporting flow.
  - The status of every incident should initially be set as 'Unclaimed.'
  - Once a crew member claims an incident, its status should change to 'Claimed.'
  - When the crew member reaches the incident location, they should be able to update the incident status to 'In Progress.'
  - After addressing the issue, the status should finally be changed to 'Resolved.'
- **Incident Report Filing**: Upon resolution, the crew should be able to submit a detailed report about the incident through the application. The report should carry information about the incident, how it was addressed, the time taken for resolution, and issues encountered during the process. This information will help generate informative analytics.
- **View and Filter Options**: It should offer users the ability to filter and sort incidents based on their status i.e., unclaimed, claimed, and resolved. Also, allow the crews to view only their claimed incidents for better individual task management.
- **User-Friendly Interface**: Keeping our end-users in mind, the application should be designed to be intuitive, easy to navigate and operate -- even for the least tech-savvy among the cleaning crews.
- **Responsiveness**: The application should be responsive, automatically adjusting the layout depending on the screen size and orientation. The hovercrafts come equipped with data terminals of varying sizes, and the crews should be able to use the application efficiently on all of them.

- Nieuwe pagina: Lijst overview alle opdrachten

- Nieuwe pagina: Meer info

### User Stories and Tasks: List the user stories and what needs to be done to fulfill them.

Title:
Beschrijving:
Forfill:

- Title:
- Beschrijving: As a user of the Incident Tracking System, I want the application to have an intuitive and user-friendly interface, ensuring that it is easy to navigate and operate, even for users who may not be tech-savvy, such as cleaning crews.
- Forfill:

### Identify the programming languages, frameworks, and platforms you'll use.

- html
- css
- JavaScript
- leaflet.js
- json

### Database Design: Include textual descriptions of tables and columns, or an Entity-Relationship Diagram (ERD).

### Planning: Create a timeline for the development process, specifying which team member is responsible for what.

### Wireframe: Create a basic wireframe sketch to guide the UI/UX design.
