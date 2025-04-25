# Spam-sms-Detection
Task Objectives :
        1.The objective is to develop an SMS classification model that identifies spam messages.
        2.The dataset consists of labeled messages categorized as spam or non-spam.
        An Expected Outcome : A robust model that accurately distinguishes between spam and legitimate messages, withwell-documented preprocessing and classification                                 approaches.
Spam-SMS-Detection/
│
├── data/
│   └── spam_sms_dataset.csv  # (or whatever the dataset filename is)
│
├── scripts/
│   └── spam_detection.py   # Main Python script
│
├── README.md
│
└── requirements.txt        # List of Python dependencies

# Prerequisites :-
            * Python 3.x installed on your system.
            * pip (Python's package installer) installed.
            * Git installed (if you plan to clone the repository).

# Dataset Preparation :-
           * Ensure that the SMS dataset file (`spam_sms_dataset.csv`) is placed in the `data/` directory.
           * If the filename is different, update the `data = pd.read_csv('spam_sms_dataset.csv', ...)` line in the `spam_detection.py` script.

# Running the Script :- 
           * Execute the main Python script:
                    '''bash python scripts/spam_detection.py '''

          * The script will:
  * Load the dataset.
  * Preprocess the text messages.
  * Train the Naive Bayes model.
  * Evaluate the model's performance.
  * Print the evaluation metrics (accuracy, classification report, confusion matrix) to the console.
