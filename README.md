# Yet Another Covid Repository With Plots And Graphs And Stuff (YACRWPAGAS) 

> YACRWPAGAS is an ambitious project that aims to plot things nicely.

## How things work

I use the notebook to plot the GIFs image by image.

Something along the lines of

```
convert -set delay '%[fx:t==(n-1) || t==0 ? 350 : 130]' -loop 0 -monitor -layers optimize -resize 900 *.png output.gif
```

using `ImageMagick` then produces nice GIFs for me.

## License and Reuse

Feel free to reuse all the code here. Probably you shouldn't anyways.
