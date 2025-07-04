# How to Create an Event

This is the rough steps in how to create a meetup event from scratch.

## Sessionize: Secure the Speaker(s), Confirm Availability, and Officially Approve

- Insure speakers submit their talks and bios via [Sessionize](https://sessionize.com/app/organizer/event/13876).
    - For special cases, an organizer can volunteer to submit on the speakers' behalf.
- Coordinate with the speaker(s) the date and venue to confirm their availability in email, CC: mailto:organizers@k8saustin.com
- When confirmed, update the Sessionize talk status to Accepted and request they formalize their agreement in Sessionize.
    - This is important if speakers want a record of their talks (which counts towards commuinity contribution).

![inform the speakers](pictures/sessionize/inform-speakers.png)

## Canva: Create Art and Upload them on Google Drive

### Canva

Create three pieces of art for the event:
1. An event banner for Bevy
1. An event logo for Bevy (reuse for LinkedIn)
1. An event banner for Meetup

Login on [Canva](https://canva.com) and look for [K8sAustin](https://www.canva.com/folder/FAF7fBq_SQc) folder.

Create a new folder under this folder with the format "YYYY-MM-DD" for the date of the meetup. For the next steps, please create the arts and save them under this folder.
We usually create a single art for both speakers, you must collect their picture from the sessionize website.

For #1, it is a `2560 x 650 px` banner, look for files named `bevy-banner-k8s-austin-meetup-<date>`, pick one and save as and edit the speakers' name, picture and companies.
*Leave the middle of the banner blank*.
Example

![bevy-banner-example](pictures/canva/bevy-banner-example.png)

For #2, it is a `1080 x 1080 px` tile for the logo. Look for files named `bevy-k8s-austin-event-logo-<date>`.
Same drill, pick one, save as and edit it with the title and date.
Example:

![bevy-logo-example](pictures/canva/bevy-logo-example.png)

For #3, it is required for the meetup page a `1200 x 675 px`. Look for files named  `meetup-banner-k8s-austin-meetup-<date>`.

### Google Drive

Create a new folder under our [Google Drive](https://drive.google.com/drive/u/0/folders/1VNMGy8GB9ehdlfabIrdEEQLDHg3KHGdq) and upload all arts, under the current year.
The same folder will contain the Google Slides presentation for the meetup.

## Create a Bevy Event

Log on [Bevy](https://community.cncf.io/accounts/dashboard/#/chapter-177/events-Live), make sure you have access to the Kubernetes Austin dashboard: 

![Kubernetes Austin Dashboard](pictures/bevy/dashboard-example.png)

It is easier to duplicate a previous event than to click at `New Event -> Meetup` and follow the prompts.
Copy and paste from the previous event, we always link the speaker's name to their LinkedIn profile.

If the event is being hosted at [Capital Factory](https://www.capitalfactory.com), please make sure their logo and address are displayed (for contractual reasons).
Desirably, if you have the name of the room, make sure it is displayed correctly and prominently.
Upload the event banner and thumbnail you made previously.
Add all the co-organizers as host. Add sponsors (whoever is paying for foods and drinks).
Use the option to RSVP, we usually limit capacity to 50 people.

## Create a K8sAustin.com/ShortURL

Once you have a URL for the event, go to [https://github.com/k8sAustin/k8saustincom/blob/main/_redirects](https://github.com/k8sAustin/k8saustincom/blob/main/_redirects) and edit file or submit a pull request. Test it: https://K8sAustin.com/ShortURL-example

## Create a Meetup Event

Log on [Meetup](https://www.meetup.com/home/), view the dashboard (like below) and click at `Create Event`.
Use the "Copy the Last Event" button or copy and paste from a previous event.
Link to the Bevy event because of CNCF ownership; we hope to migrate off Meetup.
Make sure to add descriptive topics, such as: `kuberenetes, cloud native, open source`.

![Meetup Dashboard](pictures/meetup.com/dashboard-example.png)

## Promote the Event!

[Via Buffer](posting-on-buffer.md).

Schedule (ideally three) two weeks before, one week before, a few days before the event!
Update descriptions (and graphics if you have the energy) with last minute changes or the confirmed room.
