# videoblip
Video Action Recognition using Blip and GPT-3

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LaIgr5L0QAD2EMVSy3GiPp_XKypa0wAD?usp=sharing)



# VideoBlip

VideoBlip is a script that generates natural language descriptions from videos. It does so by extracting frames from a video, passing them through the Blip recognition model, which identifies the contents of those frames, and sending those predictions to GPT-3 to generate a text description of what is happening in the video. The script allows you to upload as many files as you want at once. It could be used as a natural language metadata generator or to generate huge datasets of videos aligned with a description. But the core function of the script is to convert video content into text descriptions.

## Usage

1. First, make a copy of this notebook to replace the API key in the code.
2. Go to File, Save a copy in Drive.
3. Change `YOUR_API_KEY` to your actual OpenAI API key.
4. Run the script cell by cell and wait for the processing to finish.

## Hardware Configuration

The script requires a machine with a GPU for optimal performance. If you don't have a GPU, you can still run the script, but it may take significantly longer to complete.

## Example

Check out an example of the script in action [here](https://colab.research.google.com/drive/1LaIgr5L0QAD2EMVSy3GiPp_XKypa0wAD?usp=sharing).

## Architecture
![VideoBlip (2)](https://user-images.githubusercontent.com/113161118/224814780-de7232a9-6e6f-4dc5-82f0-d1fc7a96cf97.jpg)
## Contributions are welcome!

We're excited to have you contribute! Feel free to fork the repository, add new features, and submit pull requests. Let's make VideoBlip better together!

## License

This project is licensed under the [MIT license](https://github.com/ivfloyd/videoblip/blob/main/LICENSE).

