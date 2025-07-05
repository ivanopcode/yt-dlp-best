yt-dlp-best

A simple shell script that downloads the best available MP4 video and M4A audio from a provided URL, merges them into an MP4 container, and retains only the audio sidecar in a structured folder.

Dependencies
	•	yt-dlp
	•	ffmpeg

Make sure both are installed and available in your $PATH.

Usage

./yt-dlp-best "<media_url>"

Example:

./yt-dlp-best "https://youtu.be/example-video"

Output Structure

Downloads are organized into individual folders named using the video’s metadata:

[upload_date] [channel_name] [platform] [video_id] [video_title]/
├── [upload_date] [channel_name] [platform] [video_id] [video_title].mp4  # merged video
