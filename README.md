# Python Commands with Copy Buttons

Below are common Python commands, each in its own section with a "copy" button for convenience.

---

## 1. Run the Script
To execute the script, use the following command:

```bash
pip install -r requirements.txt
```
---
## 2. Sorting the files
To sort the all csv files, run the below command. (this sorting is based on video_name and track_id columns inside csv file)
```bash
python sort_csv_files.py <input_directory> <output_directory>
```
---
## 3. Splitting the files by label
To split the all csv files by label, run the below command
```bash
python split_csv_by_label.py <input_directory> <output_file_01> <output_file_02>
```
---
## 4. Generate the sequence
To generate the sequence, run the below command
```bash
python generate_sequences.py <input_file> <output_files> <sequence_length>
```
---
## 5. Checking the generated sequence
To check the generated sequence in order to sure the duplicacy of group, run the below command
```bash
python check_group_counts.py <input_file> <output_files> <sequence_length>

```
## 6. Appending the both generated sequence csv files
To append the generated sequence csv file, run the below command
```bash
python append_csv_files.py <input_file_01> <input_file_02> <output_file>

```
## 7. Splitting the sequence
To split the sequence of appended csv file, run the below command
```bash
python sequence_split.py <input_file_01> <input_file_02> <output_file> <splitting ratio> 
```

## 8. Uploding the files, train the model, and download the trained model
To achieve above, go to the notebook.ipynb and run the cells one by one.
```bash
python code_03.py
```

## 9. Testing model
To test the trained model, run the cells one by one.
```bash
python detect_shoplifting.py <--yolo_model> <--lstm_model> <--max_sequence_length> <--frame_skip> <--video_path> <--output_folder>
```
