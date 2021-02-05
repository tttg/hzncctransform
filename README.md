# hzncctransform
video frame_buffer data modified and using imxg2dcompositor to compositor multi videos  
This plugin name:hzncchytransform  
Hardware:Imx6q or Imx6x with IPU/GPU  
Software:kernel>4  Gstreamer1.0 imxv4l2videosrc imxg2dcompositor  
Desctiptions:  
video0 is a Infrared Camera,and output data format is gray8+Temp_data.We use our own plugin:hzncchytransform to separate gray8 added with pseudo-color,the format is RGBA,and Temp_data to be produced using appsink with tee.  
video1 is a common ov camera,and output is I420 format.  
Results:we can succedd to overlay the compositor video0 and video1 to LCD,and produce the Temp_data in appsink to uper user.  
Code: luwei860123@163.com  
QQ:420788046  
