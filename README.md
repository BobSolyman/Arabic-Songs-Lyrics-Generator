# Arabic-Lyrics-Generation

This project focuses on generating Arabic song lyrics using the GPT-2 model. The model is fine-tuned on a dataset of Arabic song lyrics, and then utilized to generate new lyrics based on given prompts. The generated lyrics aim to capture the style and essence of Arabic songs.

## Project Structure

- `arabicLyrics.csv`: Contains the dataset used for training the model.
- `NotoNaskhArabic-Regular.ttf`: The font used to display word clouds.
- `team10.ipynb`: Jupyter Notebook for exploring the dataset.
- `training-code.ipynb`: Jupyter Notebook for training and fine-tuning the GPT-2 model on the Arabic song lyrics dataset.
- `generate-text.ipynb`: Jupyter Notebook for generating Arabic song lyrics using the fine-tuned model.
- `pretrained_models/`: Directory to store the pretrained GPT-2 model - to be uploaded -.
- `Lyrics_Generation_Report.pdf`: PDF containing the final report for the project.


## Getting Started

Training the Model:
- Prepare your dataset of Arabic song lyrics and place it in the `data/` directory.
- Run the `model_training.ipynb` notebook to train and fine-tune the GPT-2 model on the dataset. Adjust the training parameters as needed.

Generating Lyrics:
- In the `lyrics_generation.ipynb` notebook, provide a prompt for the model to generate lyrics based on the fine-tuned model.
- Run the notebook to generate Arabic song lyrics and explore the results.


To reproduce the results :
1. Run the `training-code` notebook and save the fine-tuned model.
2. Run the `generate-text` notebook and load the saved model to generate your lyrics.


## Acknowledgements

- The GPT-2 model used in this project is based on the implementation by OpenAI. Check their repository for more information: [OpenAI GPT-2](https://github.com/openai/gpt-2)






link for the HABIBI dataset  http://ucrel-web.lancaster.ac.uk/habibi/
