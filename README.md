# videoblip
Video Action Recognition using Blip and GPT-3

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LaIgr5L0QAD2EMVSy3GiPp_XKypa0wAD?usp=sharing)


# VideoBlip

VideoBlip is a script that aims to extract text from videos. It does so by extracting 5 frames from a video, passing them through the Blip recognition model, sending those 5 predictions to GPT-3, and asking it to "guess" what the video is about. The good thing is that you can upload as many files as you want at once. It could be used as a natural language metadata generator, or it could be used to generate huge datasets of videos aligned with a description. But the script itself is a Google Colab notebook that does just that.

## Usage

1. First, make a copy of this notebook to replace the API key in the code.
2. Go to File, Save a copy in Drive.
3. Change the `YOUR_API_KEY` to your OpenAI API key.
4. Install the necessary dependencies by running `!pip install -r requirements.txt` in the notebook.
5. Configure the input and output directories.
6. Run the script and wait for the processing to finish.

## Hardware Configuration

The script requires a machine with a GPU for optimal performance. If you don't have a GPU, you can still run the script, but it may take significantly longer to complete.

## Example

Check out an example of the script in action [here](https://colab.research.google.com/drive/1LaIgr5L0QAD2EMVSy3GiPp_XKypa0wAD?usp=sharing).

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

This project is licensed under the [MIT license](https://github.com/ivfloyd/videoblip/blob/main/LICENSE).

