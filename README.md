# Music_Generation_AI

We train the model by providing it with midi files which are converted to matrix before train it.
<img src="Music Generation AI/Images/Keys.png" width="600" height="300"><br>
<br>
<br>
Above image shows us at what time_step which respective key is being pressed.
This in then converted to matrix to provide it to Encoder for generating music.<br>
<br>
<img src="Music Generation AI/Images/Music matrix.png" width="600" height="300">


## Generate Music

```html
python rbm.py
```
The new music midi file will be generated in output folder.
