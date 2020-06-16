# The classic tech meetup: Talks

This is the most classic form of meetups: 
multiple speakers present their topics, while sharing their slides.
After each talk there might be time for questions by the audience.

We do this for the [Rust'n'Tell][rust-n-tell], a monthly meetup of the Rust community.

## Setup

### Zoom

We use [Zoom] for the whole meetup. I have a paid account, 
allowing for unlimited[^1] time and up to 100 participants.

[^1]: 24 hours, but let's be honest.

Prior to the meetup, check these Zoom settings (I'm not listing all, just some relevant ones, make yourself familiar with the settings):

* Join before host: disabled
* Mute participants upon entry: enabled
* Chat: enabled
* Co-host: enabled
* Screen sharing - Who can share?: Host only
* Annotations: disabled
* Breakout room: enabled
* Waiting room: enabled
    * Place everyone in the waiting room
* Allow live streaming meetings: enabled
    * Select services as required, I only use "Custom Live Streaming Service"

### YouTube live streaming

We also stream the meetup to YouTube.

In your YouTube account schedule a new live stream and enter the description and details.
Disable the chat.

You will get the target URL, the stream key and the stream URL.
Note all down.
The Stream URL can be published to attendees.

## Prior to meetup

Create a new Zoom meeting. Schedule it for 30 minutes before the planned started, and 30 minutes beyond planned ending.
This will give you the link (and optional password).

Invite your attendees.
Invite your speakers and MC early for a tech check.

## Tech check

With your speakers & MC around make them all a co-host.
That will allow them to unmute and to share the screen.

Go through with everyone and let them share the screen to test that it works.
People can share a single window or the full desktop.

Start the live stream (to a "custom live streaming service").
Enter the target URL & stream key.
On YouTube check that the stream is received. It's not yet live, don't worry.

Just before start press "Recording (to the Cloud)" in Zoom to start the recording.

## Meetup start

Close to the starting time, check that speakers and admins are co-host.
At time invite everyone from the waiting room.
Then disable the waiting room for the rest of the meeting. 

Start the stream on YouTube.

## During the meetup

Signal that everything is running and hand over to the MC.
They introduce speakers, speakers share their slides and start their talk

### Q & A

The MC monitors the Zoom chat and external chat for questions.
Once the talk is finished they can relay the questions to the speaker.

### Break

After the first hour of the meetup announce a break.
We use Zoom's Breakout Rooms.
Randomly assign people and create rooms such that they should have 7-10 people assigned per room.
Not everyone will join so you will end up with 2-5 people per room that way most of the time.
As the host you can monitor the attendance in breakout rooms. Reshuffle people if you see they are alone in a breakout room.

Note: if you have a second device, use that to share a timer slide, that is then also shown on the YouTube livestream. 
Otherwise that livestream is blank and your viewers will leave and probably not come back.

1 minute before it should continue stop the breakout rooms.
It takes some time for people to leave and join back the main call (the rooms also close after 60s, moving over people)

## After the meetup

Stop the recording.
Stop the livestream.

On YouTube: hide the livestream recording (we replace it with a high-quality upload).

After some time you will be able to view the Zoom recording.
It's of much higher quality, so use that for re-upload to YouTube.
Edit it beforehand (or use YouTube's clumsy editor) to cut out the beginning and end if necessary.


[rust-n-tell]: https://berline.rs/2020/05/26/rust-and-tell.html
[Zoom]: https://zoom.us/
