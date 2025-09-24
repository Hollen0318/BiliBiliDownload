吹拉弹唱慕星银      https://space.bilibili.com/690545051?spm_id_from=333.337.0.0
水岛虹              
···bash
mamba create -n bilibili python=3.11
mamba activate bilibili
pip install yt-dlp
brew install ffmpeg
# Login to the Bilibili with your account (premium best)
yt-dlp -v --cookies-from-browser chrome -x --audio-format mp3 "URL"
```