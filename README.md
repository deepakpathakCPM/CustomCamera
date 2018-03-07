# CustomCamerag

1 ) Code for using the camera : 
              
CustomCameraActivity customCameraActivity = new CustomCameraActivity(context,FILE_PATH,fileName)
customCameraActivity.startCameraActivity()

2 ) Code for using the camera with Request code : 

CustomCameraActivity customCameraActivity = new CustomCameraActivity(context,FILE_PATH,fileName)
customCameraActivity.startCameraActivityForResult(2)

3 ) Code for using the Auto Update : 

AutoUpdateActivity autoUpdateActivity = new AutoUpdateActivity(context, appLink);
autoUpdateActivity.startAutoUpdateActivity();
