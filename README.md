# Removing Paper Lines
This is a solution to a problem posted in Stackoverflow where a user asked to remove paper lines while keeping the drawing in a good condition.

The decision was to handle the paper seperated from the drawing to get the best results using morphology operations and inpaint.

https://stackoverflow.com/questions/71425968/remove-horizontal-lines-with-open-cv/71475252#71475252

Original image

![i0RDA](https://user-images.githubusercontent.com/73304837/158277587-10f34cc7-b19f-4652-bbe7-f6be7e245734.jpg)

First Mask

![i0RDA-first mask](https://user-images.githubusercontent.com/73304837/158277649-dc6a3d74-d587-4025-8dac-3fcf8d97712a.jpg)

First inpaint

![i0RDA-first](https://user-images.githubusercontent.com/73304837/158277693-8621b095-dfe1-4611-af3e-ea50af8d79b7.jpg)

Second Mask

![i0RDA-second mask](https://user-images.githubusercontent.com/73304837/158277726-9703a8bb-7a15-4b17-9dc9-b6832a33f8a7.jpg)

Second inpaint

![i0RDA-second](https://user-images.githubusercontent.com/73304837/158277768-0432204d-c29a-4296-b1ea-c6aec234642b.jpg)
