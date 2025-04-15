🎤 Fundamental Frequency (F0) Extraction for Mother and Child Vocalizations
This Python notebook extracts the fundamental frequency (pitch) from mother and child speech audio files.
By running the codes, you can get the outputs of the mean and std of the fundamental frequency for each input audio clips.
Also (optional), you can get the pitch counter.

📦 Step 1: Install Python and Jupyter (Skip this step if you already did it)
-Install Python (if not installed yet):
-Download from https://www.python.org/downloads/
-During installation, check the option “Add Python to PATH”

Install Jupyter:
-Open a terminal (Mac/Linux) or command prompt (Windows), and run:

pip install jupyter

📦 Step 2:
Install required Python packages:
-Open a terminal (Mac/Linux) or command prompt (Windows), and run:

pip install numpy pandas matplotlib librosa

📁 Step 2: Prepare Your Files
-Put your .wav audio files into a folder.
(Please refer to given 'example_sounds/PAR' and 'example_sounds/CHI' folders. In these examples, the .wav audio clips are vocalizations from the parent (PAR folder) and the child (CHI folder), which were extracted from a long audio file)

* The .wav format is always prefered for audio processing
* To cut the parent and child audio clips need the original audio file and the annotations on the start and end time of each utterances, which were not conducted in the given codes. If it is neccessay, please ask me to share another code with you.

📓 Step 3: Run the Notebook
-Open a terminal or command prompt and run:

jupyter notebook

This will open Jupyter in your browser.

📓 Step 4: Run the given f0_extraction.ipynb
-Download the f0_extraction.ipynb and put it into the folder where you installed the jupyter (It is always the home folder)
-Open the file f0_extraction.ipynb
-Run each code cell in order by clicking "▶" or pressing Shift+Enter.
* Please pay attention to change all the path to the files and path for saving before running the codes. For the detailed locations to change, please see the notes in the codes.









