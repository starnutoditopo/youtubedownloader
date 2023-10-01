# Download mp3 files from Youtube

A python script to batch download music from YouTube.

Read the list of media to download from a text file containing a URL per line:

```text
https://youtu.be/lWA2pjMjpBs
https://youtu.be/kJQP7kiw5Fk
https://youtu.be/HCjNJDNzw8Y
https://youtu.be/DeumyOzKqgI
...
```

For each required media, the one with highest audio bit rate is downloaded and converted to mp3.

# Quick start

Open this repository as container in Visual Studio Code.
Edit a text file (eg.: `my_play_list.txt`), so that it contains a YouTube URL for each line (empty lines are ignored, as well as lines starting with '#').

Just press **F5**, or run `python download_mp3_from_youtube.py -i <inputFile> -o <outputDirectory>`; example:

```bash
python download_mp3_from_youtube.py -i my_play_list.txt -o ./output
```

Find the downloaded files in the `<outputDirectory>` folder.