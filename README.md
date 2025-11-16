2-Day Home Assignment: Active Learning for Image Classification
Below is the assignment for the next two days. The goal is to understand how you approach active learning, uncertainty-based sample selection, and training models efficiently with limited labelled data.
1- Dataset
Please use a small image classification dataset.
Preferred (Autonomous Driving):
 GTSRB – German Traffic Sign Recognition Benchmark
2- Task
Start with:
    • A small, labelled subset (around 5–10% of the dataset)
    • A large unlabelled pool
Then:
    1. Train an initial simple classifier on the labelled set.
    2. Implement an active learning loop that selects the most informative samples to label
 (e.g., uncertainty sampling, entropy, margin).
    3. Retrain or fine-tune the model as new samples are added.
    4. Track how performance changes as you acquire more labelled data.
What to Submit
    • A clear explanation of your approach and the reasoning behind your decisions
 (e.g., model choice, uncertainty method, training setup).
    • A description of your active learning loop.
    • Code (we prefer Tensorflow, but you can use Pytorch if you prefer)
    • Plots or tables showing performance as more samples are added.
    • A short justification of every key decision you make.
3- A+ Section (Strongly Encouraged)
If you want to go one step further, you may also include:
    • A brief roadmap: what you would do next if you had more time.
    • Any reflections on the limitations of your current approach and how you would address them.
This optional section helps us understand your thinking beyond the core assignment.

Alternative (Medical Imaging):
 If you prefer, you may use a small medical imaging dataset instead.
 While our preference is for an autonomous vehicle dataset, we are completely fine if you use a medical dataset.
