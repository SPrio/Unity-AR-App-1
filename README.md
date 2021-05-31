## Unity Android AR App with AR Foundation and ARCore

1. Setup Unity on your system
2. enable android build support 
3. create a 3D project
4. go to File > Build Settings > select Android
5. go to Window > Package Manager > Advanced > Show Preview packages
6. in that menu install these packages 
	1. AR Foundation 4.1.1
	2. ARCore XR plugin 4.1.1
	3. XR Plugin management 3.2.16
7. go to hierarchy bar in unity, right click there select XR > AR Session Origin
	1. expand AR Session Origin > AR Camera
	2. go to Inspector tab change Tag to Main Camera
8. go to hierarchy bar, right click there & select XR > AR Session
9. go to hierarchy bar, right click there & select 3D Object > Cube
	1. click on Cube, go to inspector tab
	2. in Transform > Change Position to X: 0, Y: 0, Z: 1
	3. in Transform > Change Scale to X: 0.2, Y: 0.2, Z: 0.2
	4. change the rotation a little bit of the cube
10. enable usb debugging in android phone & use android phone which supports ARCore
11. Then in unity go to File > Build Settings > Android > Run Device > Refresh > Select your Physical Device
12. Then in unity  go to File > Build Settings > Player Settings > XR Plug-in Management > Enable ARCore
13. Then Build and run and check your android phone to preview the app
14. if any error occurs while building the app, check this video to resolve it https://youtu.be/c6Zbqm5Fys8

<hr>

Thank you, Keep Developing Apps & Enjoy :)
