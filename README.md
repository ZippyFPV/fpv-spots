
[Click here for demo](fpv-spots.herokuapp.com)
# What is FPV-SPOTS?
I am an FPV drone pilot. I wanted to devise a way to log locations of flying spots that I visit. The idea is to have users create a profile and log locations that they have flown with a video url if applicable to show other users what the location looks like. I want this to be a social platform so users will be able to browse their favorite pilots and see their locations.

# Why is this app useful?
The FPV drone racing community is a tight knit group that prides itself on sharing knowledge and information.I wanted to facilitate this implementation to encourage sharing. There is an app out there now that allows you to create locations but it restricts you to having to do it while you are at the location itself. I don't like that. I want users to be able to curate and edit their footage and post something that is quality at the time of their choosing.

# Accomplishments
In the week that I worked on this project I have accomplished :

- User can find their location on map and it finds the lat and long.

- Form includes :

  Pilot Name
  || Video Link URL
  || Location Safety
  || Location
- Users can Post and Get

- Responsive page layout

- Created design assets (e.g. prop, flag vectors). I used sketch as the design and mockup software.

- User can create a pin

- Users URL gets converted into a hyperlink in the info window.

- All user pins are displayed by default.

- Connected with the Google Api for map.

- When user clicks on link in the info box, the video opens in a new window (Dope suggestion Justin. Thanks!)

- Added links to Github Repo, Zippymultirotors.com, and LinkedIn


# What features I will add?
I plan on seeing this app all the way through to production. With that being said this is my todo for the next week.


- Implement having geolocation of the user be found and automatically snap to that location once it is established.
(Example: User can see locations near them.)

- Search by zipcode if user doesn't allow geolocation.

- Filter the pin results that get displayed by Pilots || Locations

- Add Facebook login as that is the main platform of sharing for the drone community.

- Create a landing page

- Refactor layout to make it mobile friendly.



# What Code I like

```bash
// Create popup windows for each record
var  contentString =
    `<p><b>Pilot :</b>${user.pilot}
     <br><br><b>Safe? :</b>${user.safe}
    <br><br><b>Video: </b><a target="_blank" href =${user.url}> Link </a></p>`
```

by Benjamin Tovar
