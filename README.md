# crash-log-minecolonies
my crash
/ Don't be sad, have a hug! <3

Time: 6/23/20 5:09 AM
Description: mouseClicked event handler

java.lang.NullPointerException: mouseClicked event handler
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding.updateResources(WindowBuildBuilding.java:278) ~[?:1.15.2-0.11.960] {re:classloading}
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding.onStyleDropDownChanged(WindowBuildBuilding.java:390) ~[?:1.15.2-0.11.960] {re:classloading}
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding$$Lambda$20831/240589676.accept(Unknown Source) ~[?:?] {}
	at com.ldtteam.blockout.views.DropDownList.setSelectedIndex(DropDownList.java:215) ~[?:0.10.324-ALPHA] {re:classloading}
	at com.ldtteam.blockout.views.DropDownList.selectNext(DropDownList.java:245) ~[?:0.10.324-ALPHA] {re:classloading}
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding.nextStyle(WindowBuildBuilding.java:398) ~[?:1.15.2-0.11.960] {re:classloading}
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding$$Lambda$20830/1543870182.run(Unknown Source) ~[?:?] {}
	at com.minecolonies.coremod.client.gui.AbstractWindowSkeleton.lambda$registerButton$0(AbstractWindowSkeleton.java:67) ~[?:1.15.2-0.11.960] {re:classloading}
	at com.minecolonies.coremod.client.gui.AbstractWindowSkeleton$$Lambda$20415/327996003.accept(Unknown Source) ~[?:?] {}
	at com.minecolonies.coremod.client.gui.AbstractWindowSkeleton.onButtonClicked(AbstractWindowSkeleton.java:106) ~[?:1.15.2-0.11.960] {re:classloading}
	at com.ldtteam.blockout.controls.Button.handleClick(Button.java:95) ~[?:0.10.324-ALPHA] {re:classloading}
	at com.ldtteam.blockout.Pane.click(Pane.java:508) ~[?:0.10.324-ALPHA] {re:classloading}
	at com.ldtteam.blockout.views.View$$Lambda$20438/2056119217.accept(Unknown Source) ~[?:?] {}
	at com.ldtteam.blockout.views.View.mouseEventProcessor(View.java:347) ~[?:0.10.324-ALPHA] {re:classloading}
	at com.ldtteam.blockout.views.View.mouseClickableEventHandler(View.java:300) ~[?:0.10.324-ALPHA] {re:classloading}
	at com.ldtteam.blockout.views.View.click(View.java:162) ~[?:0.10.324-ALPHA] {re:classloading}
	at com.ldtteam.blockout.BOScreen.mouseClicked(BOScreen.java:175) ~[?:0.10.324-ALPHA] {re:classloading}
	at net.minecraft.client.MouseHelper.lambda$mouseButtonCallback$0(MouseHelper.java:82) ~[?:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHelper$$Lambda$17102/566462941.run(Unknown Source) ~[?:?] {}
	at net.minecraft.client.gui.screen.Screen.wrapScreenError(Screen.java:446) ~[?:?] {re:classloading,pl:accesstransformer:B,xf:fml:blur:hookBackgroundColor,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHelper.func_198023_a(MouseHelper.java:80) ~[?:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHelper.lambda$null$4(MouseHelper.java:163) ~[?:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHelper$$Lambda$17101/1268847780.run(Unknown Source) ~[?:?] {}
	at net.minecraft.util.concurrent.ThreadTaskExecutor.execute(SourceFile:94) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.client.MouseHelper.lambda$registerCallbacks$5(MouseHelper.java:162) ~[?:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHelper$$Lambda$13635/1764746512.invoke(Unknown Source) ~[?:?] {}
	at org.lwjgl.glfw.GLFWMouseButtonCallbackI.callback(GLFWMouseButtonCallbackI.java:36) ~[lwjgl-glfw-3.2.2.jar:build 10] {}
	at org.lwjgl.system.JNI.invokeV(Native Method) ~[lwjgl-3.2.2.jar:build 10] {}
	at org.lwjgl.glfw.GLFW.glfwPollEvents(GLFW.java:3101) ~[lwjgl-glfw-3.2.2.jar:build 10] {}
	at com.mojang.blaze3d.systems.RenderSystem.flipFrame(SourceFile:105) ~[?:?] {re:classloading}
	at net.minecraft.client.MainWindow.func_227802_e_(MainWindow.java:296) ~[?:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.func_195542_b(Minecraft.java:946) [?:?] {re:classloading,pl:accesstransformer:B,xf:fml:codechickenlib:IItemRenderer,xf:fml:randompatches:RandomPatches Minecraft Transformer,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:553) [?:?] {re:classloading,pl:accesstransformer:B,xf:fml:codechickenlib:IItemRenderer,xf:fml:randompatches:RandomPatches Minecraft Transformer,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(SourceFile:204) [?:?] {re:classloading}
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_51] {}
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[?:1.8.0_51] {}
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:1.8.0_51] {}
	at java.lang.reflect.Method.invoke(Method.java:497) ~[?:1.8.0_51] {}
	at net.minecraftforge.fml.loading.FMLClientLaunchProvider.lambda$launchService$0(FMLClientLaunchProvider.java:51) [forge-1.15.2-31.2.21.jar:31.2] {}
	at net.minecraftforge.fml.loading.FMLClientLaunchProvider$$Lambda$467/1503057650.call(Unknown Source) [forge-1.15.2-31.2.21.jar:31.2] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:37) [modlauncher-5.1.0.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:54) [modlauncher-5.1.0.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:72) [modlauncher-5.1.0.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:81) [modlauncher-5.1.0.jar:?] {re:classloading}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:65) [modlauncher-5.1.0.jar:?] {re:classloading}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding.updateResources(WindowBuildBuilding.java:278)
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding.onStyleDropDownChanged(WindowBuildBuilding.java:390)
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding$$Lambda$20831/240589676.accept(Unknown Source)
	at com.ldtteam.blockout.views.DropDownList.setSelectedIndex(DropDownList.java:215)
	at com.ldtteam.blockout.views.DropDownList.selectNext(DropDownList.java:245)
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding.nextStyle(WindowBuildBuilding.java:398)
	at com.minecolonies.coremod.client.gui.WindowBuildBuilding$$Lambda$20830/1543870182.run(Unknown Source)
	at com.minecolonies.coremod.client.gui.AbstractWindowSkeleton.lambda$registerButton$0(AbstractWindowSkeleton.java:67)
	at com.minecolonies.coremod.client.gui.AbstractWindowSkeleton$$Lambda$20415/327996003.accept(Unknown Source)
	at com.minecolonies.coremod.client.gui.AbstractWindowSkeleton.onButtonClicked(AbstractWindowSkeleton.java:106)
	at com.ldtteam.blockout.controls.Button.handleClick(Button.java:95)
	at com.ldtteam.blockout.Pane.click(Pane.java:508)
