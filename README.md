# **Easy Stable Diffusion SD Upscale Notebook (a txt2imgHD and GoBig alternative)**

This colab is a version of Daswer123's notebook (commit 247) that has been modified to allow for easy access to AUTOMATIC1111's WebUI version which includes an unedited version of "SD Upscale". SD Upscale is a custom implementation of txt2imgHD, which is similar to GoBig and has quite a few options. Basically, it splits the image up into tiles, upscales the tiles, running stable diffusion on them, which adds details. Then it sews the pieces back together again, giving a nice large, **detailed** image.

This notebook isn't going to be updated (I don't know how to code). It only serves to allow easier access to the upscaler, which was hard for a noob like me to find or activate in a currently available colab notebook.  

It is basically a frozen version of Daswer123's notebook with simple modifications to re-arrange the "variant" cells at the end and make it so they are more easily accessible and prominent, while adding a few minor fixes so it would run.

It only serves as a temporary thing to make SD upscale a bit easier to run until the main notebooks are updated by their authors, and to prevent other updates from breaking potentially breaking things in the meantime. 

If you want to use it for purposes other than quick access to the special upscaling, better and newer options exist elsewhere.

Here are some relevant links:

https://github.com/AUTOMATIC1111/stable-diffusion-webui

https://github.com/hlky/stable-diffusion

https://github.com/daswer123/stable-diffusion-colab

https://github.com/WitheringCesspool/stable-diffusion-gobig-txt2imghd
