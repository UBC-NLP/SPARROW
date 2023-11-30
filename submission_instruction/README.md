## Submission Instructions

* We calculate scores for each of the tasks based on their individual metrics. These scores are then averaged to obtain SPARROW score.
* On the main leaderboard, only the submission that covers all 169 tasks is shown or ranked by SPARROW score.
* The submissions for each individual task are displayed and ranked on the corresponding task leaderboard based on the task-specific metric.
* The results of all 169 tasks are required to obtain the SPARROW score and appear on the main/full leaderboard.
* The file name should follow the format {task_identifier}\_predictions.txt. For example, the file name for the predictions of task dangerous-2020-alshehri-ara should be dangerous-2020-alshehri-ara_predictions.txt. You can find all the task identifier names in the task page. Each row in the file should represent the predicted label for a single sample in the test set. The order of the rows in the file should match the order of the samples in the test set. The number of rows in the file should be equal to the number of samples in the test set. The names of the predicted labels should exactly match the names of the labels in the training set. For example, the label set for task dangerous-2020-alshehri-ara is {Dangerous, Not}, then the predicted labels should be either "Dangerous" or "Not".
* Submit a compressed ZIP file containing all your prediction text files, whether there’s one or multiple. Ensure you directly zip the text files, not the folder containing them.
* Submissions are private by default.
* Competitors may choose to make their submission public.
* Submissions are permanent and cannot be deleted.
* We provide a submission example at [SPARROW’s GitHub repo](https://github.com/UBC-NLP/SPARROW/blob/main/submission_instruction/Bernice_submisson.zip). This submission is one of 3 runs of fine-tuning [Bernice](https://huggingface.co/jhu-clsp/bernice). It obtain a SPARROW score of 70.24.
* If you face any issues for submission, please feel free to open a issue in [SPARROW's GitHub repo](https://github.com/UBC-NLP/SPARROW/).