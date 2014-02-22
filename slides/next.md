## Next Step

![image diff](images/diff.png "Image Diff")

### Image Comparsion

* GitHub

* GraphicsMagick (http://graphicsmagick.org)

* ImageMagick (http://imagemagick.org)

note:
    problem is small changes in the UI will be difficult to distinguish
    when we are looking at the image diffs
    something like a colon can will break the screenshots and we dont want to strain our eyes

    solution is to use image processing to visually highlight the differences between images
    making it more obvious and faster to check

    future
    different screen resolutions set in browser for testing responsive design

    ultimately these can be run as part of our CI
    notified of any broken screenshots just as you would any other breaking test
    emails/growls etc
