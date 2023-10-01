# Download mp3 files from Youtube

A python script to download music from youtube

# Quick start

Open this repository as container in Visual Studio Code.
Edit a text file (eg.: `my_play_list.txt`), so that it contains a youtube URL for each line (empty lines are ignored, as well as lines starting with '#').

Just press **F5**, or run `python download_mp3_from_youtube.py -i <inputFile> -o <outputDirectory>`; example:

```bash
python download_mp3_from_youtube.py -i my_play_list.txt -o ./output
```

Find the downloaded files in the `<outputDirectory>` folder.