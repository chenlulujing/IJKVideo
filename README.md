# IJKVideo 视频播放器
底层为[Bilibili/ijkplayer](https://github.com/Bilibili/ijkplayer)，封装视频View
Bilibili/ijkplayer原来项目缺失so文件，如果不用complie方式的话，需要手动生成。生成步骤原项目里也有说明，这里再说一下：

git clone https://github.com/Bilibili/ijkplayer.git ijkplayer-android
<br>
cd ijkplayer-android
<br>
git checkout -B latest k0.7.6
<br>
<br>

./init-android.sh
<br>
<br>

cd android/contrib
<br>
./compile-ffmpeg.sh clean
<br>
./compile-ffmpeg.sh all
<br>
<br>

cd ..
<br>
./compile-ijk.sh all
<br>
<br>
如有疑问可参考文献：
<br>
[小试ijkplayer编译](http://avenwu.net/ijkplayer/2015/05/07/hands_on_ijkplayer_preparation/)
<br>
[ windows下用cygwin编译android版ijkplayer]()
