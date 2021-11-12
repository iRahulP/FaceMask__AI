
# FaceMask__AI :: A Convolutional Network for Face Mask Detection - Phase 1

## Files

- `Dataset.zip`
- `face_mask_ai_pytorch_cnn.ipynb`

## Requirements

- [Google Colab](https://colab.research.google.com/)
- [Google Drive](https://drive.google.com/)
- prerequisites : a folder named "AI" in the root directory of drive which will be used for dataset.

## Instructions

- Create an empty directory `AI` in the root of your google drive
- Go to colab and upload the file `face_mask_ai_pytorch_cnn.ipynb` to open the jupyter notebook or go to this [Project Link](https://colab.research.google.com/drive/1FQGmTS9ClqgZnWCFMV-7S3me0D2Vshi0?authuser=2#scrollTo=4zcyjzUK5_cb) to open file in colab automatically
- Run the first cell to mount your google drive folder, it would prompt you with a URL to give access permissions to your google drive
- Copy the authorisation code from that URL in cell's output to finish mounting the drive.
- The project uses your account's google drive to download the dataset and uses `AI` as its working directory.
- Run each cell of the notebook on colab one after the other
- There is an option to run all cells at once in google colab, to do that go to `Runtime -> Run all (Ctrl +F9)`
- Each cell is annotated with description of what the cell does
- For subsequent runs don't run the cell `Loading the dataset` as all the images would have been downloaded in your first run.

### Alt. Method:
- Use Anaconda Navigator, use the root environment.
- Click _Open with Jupyter Notebook_
- Navigate to `AI_FaceMask.ipynb` and run the cells as mentioned below - The Colab version runs on cpu whereas the Repository version runs on GPU consuming cudo:0 device.
- Both the Python notebooks have been tweaked as per the usage of CPU and GPU respectively.
