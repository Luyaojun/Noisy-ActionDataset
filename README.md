# Noisy-ActionDataset
The dataset collected at the Muroran Institute of Technology during 2017,has been captured using a common digital camera.
It includes 7 activities:pick up,put on,walk,play tennis,push,tight lace,bow.
During acquisition, 4subjects were asked to perform the above actions for 3 times.
As for the specific activity, we changed the conditions of each time.
And three conditions as : uncovered , covered with barrier , covered with people.

This resulted in a total of 84 activity samples.

Each filename is in the form as a<activity_id>_p<people_id>_t<times_id>.formstring.
The formstring parameter depends on the type of provided information:

	.mov 1920*1080 RGB video
	.json the joints keypoint data output by Openpose.
