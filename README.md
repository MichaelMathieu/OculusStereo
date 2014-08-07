Run :
make
optirun ./OculusWolrdDemo.sh

Important Files :
Samples/OculusWorldDemo/OculusWorldDemo.cpp -> function RenderEyeView (reads webcam, renders texture)
Samples/OculusWorldDemo/OculusWorldDemo_Scene.cpp -> function PopulateVideo1 (initializes the renderer we use) and InitCapture (init the webcams, change the webcam id here)

Might be useful :
Samples/CommonSrc/Render/Render_GL_Device.*
Samples/CommonSrc/Render/Render_Device.*
Samples/CommonSrc/Platform/Platform_Linux.*