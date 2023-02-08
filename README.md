# Image Classifier to detect rainbow trout or brown trout
## Based on Lesson #1 of the fast.ai Practical Deep Learning for Coders course https://course.fast.ai

The model seemed to do ok at identifying a brown trout, but it could definitely use some improvements. The biggest area of need is curating a better dataset to train on, and this is obvious when looking at dls.show_batch. Two of those images are completely wrong (one is a fishing lure and the other is a lake cabin - I'm guessing that lake is known for trout) and I assume there are other images that are limiting the model during training. 
