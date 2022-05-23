# BackgroundLocation
 Keep a service running when the app is killed — without disabling battery optimisation
 
I had learnt from my mistake the first time, there wasn’t a straight-forward (legal) way to keep a background service running without the user’s knowledge. So I had to use ForegroundServices to keep the process running, which also kept the user informed why this service was running even after they killed the app.
I used @supersami/rn-foreground-service library for this.
Here’s a blog on how you can create an everlasting service which can do background task using the above library. (Link to the blog)
