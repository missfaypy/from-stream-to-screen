This research investigates the feasibility of
using a Raspberry Pi 4 to retrieve and
display Spotify album cover art in realtime.
By leveraging the Spotify Web API
and an external RGB matrix display, the
system visualizes the artwork of the currently
playing tracks onto the external display.
The project demonstrates how lowcost
embedded hardware can be integrated
with online streaming services to create an
appealing digital media product. The results
confirm that Raspberry Pi–based systems
are well suited to transfer visuals onto
LED displays and open up exciting potential
for future enhancements, such as improved
visual quality and the integration
of animated, real-time display of content

**Material**

- Raspberry Pi 4 with power supply
- 64 x 64 RGB Matrix
- Matrix Bonnet with 5V Power Supply
- 16-pin GPIO ribbon cable
- JST-XH 2-pin connector
- External Screen, Keybord and Mouse
- Micro SD Card
- Soldering Kit


**Setup**

* Spotify Developer Dashboard
* Create application on https://developer.spotify.com/dashboard
* Set User Credentials settings
* Redirect URI: `http://127.0.0.1/callback`

**Install**

* SSH into Raspberry Pi
* Clone repo
  `git clone  https://github.com/ryanwa18/spotipi.git`
* Enter directory
  `cd spotipi`
* Generate token
  `bash generate-token.sh`
* Authenticate via browser
* `.cache` file created

**Software Install**

* Run setup
  `cd spotipi`
  `sudo bash setup.sh`

**Web App**

* Open browser
  `http://<raspberrypi_hostname or ip_address>`

**Ping Test**
