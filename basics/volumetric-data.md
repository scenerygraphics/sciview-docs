# Volumetric Data

Let's start with our trusty ImageJ toolbar and an empty sciview scene.

![](../.gitbook/assets/imagej-empty-sciview.png)

Now open the script editor by first clicking on the ImageJ toolbar then pressing "\[". Download and open this script in the script editor to generate a 3D image volume that we can use.

![](../.gitbook/assets/open-generate-test-volume-script.png)

Now press "Run" or Ctrl + R

![](../.gitbook/assets/generate-test-volume-output.png)

You can close the script editor, then "Add volume" in sciview.

![](../.gitbook/assets/add-volume.png)

Then you will get a dialog where you can change the resolution of your volume's voxels (for example, if you are using confocal microscopy data, your z-resolution will be much larger)

![](../.gitbook/assets/add-volume-dialog.png)

Your volume should open up in the sciview window

![](../.gitbook/assets/opened-volume-in-sciview.png)

Now let's do something fun. Start an animation to circle around your volume

![](../.gitbook/assets/circle-around-volume.png)

Start recording a video

![](../.gitbook/assets/start-recording-video.png)

After some time, stop recording the video

![](../.gitbook/assets/stop-recording-video.png)

## Changing colormap

Let's change the colormap of a volume

![](../.gitbook/assets/set-colormap.png)

Voila, now we have a new colormap

![](../.gitbook/assets/red-green-colormap.png)

## Changing transfer function

Let's change the transfer function

![](../.gitbook/assets/set-transfer-function.png)

Voila, now we have a new transfer function

![](../.gitbook/assets/adjusted-transfer-function.png)

## What about timeseries?

No problem! Try the "Volume Timeseries" demo

![](../.gitbook/assets/demo-timeseries.png)

You'll get a volume that looks like this

![](../.gitbook/assets/opened-demo-timeseries.png)

Now press play and enjoy

![](../.gitbook/assets/play-demo-timeseries.png)
