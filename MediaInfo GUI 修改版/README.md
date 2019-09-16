### 此项目是自己根据MediaInfo官方版本进行二次修改，简单处理，生成视频信息
---
### 基本代码说明**


#### General;头部

    "File Name................: %FileName%\r\n 文件名
    Duration..................: %Duration/String3% (HH:MM:SS.FFF) 时间长度
    File Size.................: %FileSize/String%\r\n"  文件大小

#### Video;视频部分

    "Video Codec...............: %Format% %Format_Profile%\r\n  视频编码
    BitDepth..................: %BitDepth/String%  位数
    Frame Rate................: %FrameRate% fps  帧率
    Bit Rate..................: %BitRate/String%  码率
    Resolution................: %Width% x %Height% (%DisplayAspectRatio/String%)\r\n"  视频尺寸

#### Audio;音频部分
    Audio#%StreamKindPos%..................:［%Language/String4%］%BitRate/String% %Channel(s)/String% %Format_Commercial% %SamplingRate/String%\r\n
    语言 / 码率 / 声道数 / 音频格式 / 赫兹
#### Text;字幕部分
    Subtitle#%StreamKindPos%...............:［%Language/String2%］%Title%\r\n 字幕语言

#### Begin;尾部注释
    Source....................: WEB-DL  来源
    Uploader..................: xiaomeng  个人标签名字

### 效果预览
    
    File Name.................: 001
    Duration..................: 01:09:27.831 (HH:MM:SS.FFF)
    File Size.................: 1.83 GiB
    Video Codec...............: AVC High@L4
    BitDepth..................: 8 bits
    Frame Rate................: 29.970 fps
    Bit Rate..................: 3 775 kb/s
    Resolution................: 1920 x 1080 (16:9)
    Source....................: WEB-DL
    Uploader..................: xiaomengya
    
### 整体代码

    File Name.................: %FileName%
    Duration..................: %Duration/String3% (HH:MM:SS.FFF)
    File Size.................: %FileSize/String%\r\n
    Video Codec...............: %Format% %Format_Profile%
    BitDepth..................: %BitDepth/String%
    Frame Rate................: %FrameRate% fps
    Bit Rate..................: %BitRate/String%
    Resolution................: %Width% x %Height% (%DisplayAspectRatio/String%)\r\n
    Audio#%StreamKindPos%..................:［%Language/String4%］%BitRate/String% %Channel(s)/String% %Format_Commercial% %SamplingRate/String%
    Subtitle#%StreamKindPos%...............:［%Language/String2%］%Title%
    Source....................: WEB-DL
    Uploader..................: xiaomeng
