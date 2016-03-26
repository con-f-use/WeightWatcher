# WeightWatcher #

Device to log the weight and acceleration of bar and dumbbells.

The WeightWatcher is in its concept stage.
The design will be made public here, once a working prototype exists.


## Concept ##

### Summary ###

The WeightWatcher is a little cylindric device that attaches to one end of a barbell or dumbell.
When a weight palte is slit onto or off the WeightWatcher end of the bell, the device is activated.
It then detects whether the plate is remoced or added as well as a tag on the weight plate that specifyes the weight.
In order to require only one WeightWatcher per bell, we assume the weight is put on symmetrically on both sides of the bell, i.e for every detected plate the device assumes another one of the same type on the other end.
A similar tag as that of the weights might be read by the weight Watcher to identify the current user of the bell.
The Watcher indicates successful reading of any tag, wight or user, by flashing an LED or via an audibale signal.
The weight and user data is then sent to a central receiver (smartphone, server of the gym, ...) along with the individual ID of the Weight watcher.
This data can then be followed by continous accelerometer data during training.
The central receiver can log the Watcher ID, user, weight and accelerometer along with the time of receival for later analysis.
The accelerometer data can give information about the number and quality of training repetitions.
Analizing the data allows for a more effective training and progress tracking without the effort of loggin everything by hand in a training journal.

### Hardware Design Considerations ###
Work in progress.

### Frimware Design Considerations ###
Work in progress.

### Software Design Considerations ###
Work in progress.


## Contributors ##

 - [con-f-use](mailto:con-f-use@gmx.net)
 - Thomas K.

So far, this is a one-man project.

However, any help or ideas are appreciated and will be credited here.

There is a [brain stroming thread](http://www.eevblog.com/forum/projects/brainstorming-for-barbelldumbell-training-logger/) on the [EEVBlog's Forum](http://www.eevblog.com/forum).


## License ##

Copyright (c) 2016 con-f-use@gmx.net

The project concept along with all files in this repository are owned by the copy right holder.

This work is licensed under the Creative Commons Attribution 4.0 International License.
A copy of this license should be included with the distribution of this text.
If not, visit http://creativecommons.org/licenses/by/4.0/.

THE WORK INCLUDING ANY DERIVED HARDWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">WeightWatcher</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/con-f-use/WeightWatcher" property="cc:attributionName" rel="cc:attributionURL">con-f-use</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
