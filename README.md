# yt-dlp-best

A minimal Bash wrapper around **yt-dlp** + **FFmpeg** that

* grabs the **best available** MP4 video track and M4A audio track  
* merges them into a single `.mp4` (no re-encode)  
* downloads the highest-resolution thumbnail / storyboard sheet (if present)  
* puts everything into a deterministic, human-readable folder

---

## Dependencies

* **[yt-dlp](https://github.com/yt-dlp/yt-dlp)**
* **FFmpeg** (any modern build)  

Ensure both binaries are discoverable in your `$PATH`.

---

## Installation

```bash
git clone https://github.com/your-org/yt-dlp-best.git
cd yt-dlp-best
chmod +x yt-dlp-best
```

