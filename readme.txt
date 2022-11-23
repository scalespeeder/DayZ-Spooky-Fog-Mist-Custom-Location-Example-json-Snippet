DayZ Spooky Mist & Fog json Mod Changelog & Terms Of Use

Limited Testing on PC Chernarus Local Server DAYZ Version 1.19 Nov 2022.

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded files or snippets could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded files or snippets neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

This code snippet will spawn in a spooky mist in and around the coordinates of your choice.

To install these snippets simply change the name at the top & replace the X & Z with coordinates from Izurvive ( https://dayz.ginfo.gg/   press ctrl c to coopy cursor position to clipboard)
and then insert the whole code snippet into the correct position (near the top on a line after the first [ Bracket)
 in your cfgEffectArea.json file and restart your server.
 
 { 	"AreaName": "Chern-Graveyard", 
			"Type": "ContaminatedArea_Static", 
			"TriggerType": "effecttrigger",
			"Data": { 
				"Pos": [ X, 0, Z ],
				"Radius": 100,
				"PosHeight": 22,
				"NegHeight": 10,
				"InnerRingCount": 1,
				"InnerPartDist": 50,
				"OuterRingToggle": 1, 
				"OuterPartDist": 50, 
				"OuterOffset": 0, 
				"VerticalLayers": 0,
				"VerticalOffset": 0,
				"ParticleName": "graphics/particles/spooky_mist"
				},
			"PlayerData": {
				"AroundPartName": "graphics/particles/",
				"TinyPartName": "graphics/particles/",
				"PPERequesterType": ""
			}
		},
 
 
 
 
 Thanks, Rob.
