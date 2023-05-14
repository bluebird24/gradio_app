# gradio_app

What this app will do ? in shot this a manual text labeling app.
1. Pick 10 random text samples from a CSV file and display them to users.
2. Users will select labels for these 10 samples from a drop-down and the response label will be stored as label 1.
3. If we already have label 1 for the sample then the response will be stored as  label 2
3. Each sample will be displayed at max 2 times to the users and if we have both labels 1 and 2 for a sample then that sample will be removed from the main CSV file and stored in the output CSV file as result with both labels 1 and 2.

