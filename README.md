Files: ./log_system/log.h
	   ./third_party/**
	   main.c
commit: ac4aad4

1. Copy the folder "third_party", "log_system" to your project and replace the main.c with the attached.
2. Modify the project settings, add ${workspace_loc:/${ProjName}/third_party/RTT}/"${workspace_loc:/${ProjName}/log_system}" to include paths
3. Modify the hal-config.h VCOM symbol if needed.
4. Copy the retargetserial related files(retarget*.* from C:\SiliconLabs\SimplicityStudio\v4\developer\sdks\gecko_sdk_suite\v2.2\hardware\kit\common\drivers) to the project.
