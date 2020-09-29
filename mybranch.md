SkPixmap

https://github.com/google/skia/blob/52a4379f03f7cd4e1c67eb69a756abc5838a658f/experimental/ffmpeg/SkVideoEncoder.cpp#L258



https://forums.xamarin.com/discussion/95395/creating-skbitmap-on-user-supplied-memory

packages/rawvideo-demo/page_handler.cc  void writeFile(const SkBitmap& bmp1){


```
git clone https://github.com/kimown/skia.git
cd skia
git checkout mybranch

tools/install_dependencies.sh



ffmpeg -y -f lavfi  -i color=0xFF0000:s=720x1280 -vframes 1 image0.png
ffmpeg -y -f lavfi  -i color=0x00FF00:s=720x1280 -vframes 1 image0.png
ffmpeg -y -f lavfi  -i color=0x0000FF:s=720x1280 -vframes 1 image0.png
cp -r  image0.png image1.png
cp -r  image0.png image2.png
cp -r  image0.png image3.png
cp -r  image0.png image4.png
cp -r  image0.png image5.png
cp -r  image0.png image6.png


../out/Static/skottie2movie --input ${PWD}/data.json --gpu  --output a_gpu.mp4 -v
../out/Static/skottie2movie --input ${PWD}/data.json --gpu  --output a_gpu_red.mp4 -v
../out/Static/skottie2movie --input ${PWD}/data.json --gpu  --output a_gpu_green.mp4 -v
../out/Static/skottie2movie --input ${PWD}/data.json --gpu  --output a_gpu_blue.mp4 -v



ffmpeg -y -f rawvideo -pixel_format bgra -video_size 720x1280 -i /tmp/frame_0.rgba -frames:v 1 frame_0.rgba.png

rgba


ls /tmp/frame_*.bgra | sort -V | xargs cat | ffmpeg -y -framerate 25 -f rawvideo -pixel_format bgra -video_size 720x1280 -i - a.mp4

vi /tmp/frame_0.rgba

red:   0000 fdff 0000 fdff 0000 fdff 0000 fdff
green: 00fd 00ff 00fd 00ff 00fd 00ff 00fd 00ff
blue:  fe00 00ff fe00 00ff fe00 00ff fe00 00ff
```