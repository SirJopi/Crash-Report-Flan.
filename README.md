Crash-Report-Flan.
==================

---- Minecraft Crash Report ----
// You're mean.

Time: 06/09/13 16:50
Description: Rendering screen

java.lang.NullPointerException
	at co.uk.flansmods.common.ItemPlane.func_77624_a(ItemPlane.java:57)
	at net.minecraft.item.ItemStack.func_82840_a(ItemStack.java:662)
	at net.minecraft.client.gui.inventory.GuiContainer.func_74184_a(GuiContainer.java:226)
	at net.minecraft.client.gui.inventory.GuiContainerCreative.func_74184_a(GuiContainerCreative.java:764)
	at net.minecraft.client.gui.inventory.GuiContainer.func_73863_a(GuiContainer.java:202)
	at net.minecraft.client.renderer.InventoryEffectRenderer.func_73863_a(SourceFile:31)
	at net.minecraft.client.gui.inventory.GuiContainerCreative.func_73863_a(GuiContainerCreative.java:669)
	at net.minecraft.client.renderer.EntityRenderer.func_78480_b(EntityRenderer.java:1036)
	at net.minecraft.client.Minecraft.func_71411_J(Minecraft.java:934)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:826)
	at net.minecraft.client.main.Main.main(SourceFile:101)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:57)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:18)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Stacktrace:
	at co.uk.flansmods.common.ItemPlane.func_77624_a(ItemPlane.java:57)
	at net.minecraft.item.ItemStack.func_82840_a(ItemStack.java:662)
	at net.minecraft.client.gui.inventory.GuiContainer.func_74184_a(GuiContainer.java:226)
	at net.minecraft.client.gui.inventory.GuiContainerCreative.func_74184_a(GuiContainerCreative.java:764)
	at net.minecraft.client.gui.inventory.GuiContainer.func_73863_a(GuiContainer.java:202)
	at net.minecraft.client.renderer.InventoryEffectRenderer.func_73863_a(SourceFile:31)
	at net.minecraft.client.gui.inventory.GuiContainerCreative.func_73863_a(GuiContainerCreative.java:669)

-- Screen render details --
Details:
	Screen name: net.minecraft.client.gui.inventory.GuiContainerCreative
	Mouse location: Scaled: (194, 189). Absolute: (582, 267)
	Screen size: Scaled: (534, 279). Absolute: (1600, 837). Scale factor of 3

-- Affected level --
Details:
	Level name: MpServer
	All players: 2 total; [EntityClientPlayerMP['jopi'/524, l='MpServer', x=3.11, y=120.62, z=41.26], EntityOtherPlayerMP['teemboh1662'/219, l='MpServer', x=2.81, y=118.78, z=30.75]]
	Chunk stats: MultiplayerChunkCache: 395
	Level seed: 0
	Level generator: ID 00 - default, ver 1. Features enabled: false
	Level generator options: 
	Level spawn location: World: (80,64,256), Chunk: (at 0,4,0 in 5,16; contains blocks 80,0,256 to 95,255,271), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,0,0 to 511,255,511)
	Level time: 263639 game time, 433473 day time
	Level dimension: 0
	Level storage version: 0x00000 - Unknown?
	Level weather: Rain time: 0 (now: false), thunder time: 0 (now: false)
	Level game mode: Game mode: creative (ID 1). Hardcore: false. Cheats: false
	Forced entities: 133 total; [EntityClientPlayerMP['jopi'/524, l='MpServer', x=3.11, y=120.62, z=41.26], EntityCreeper['Creeper'/279, l='MpServer', x=-72.10, y=78.00, z=-35.78], EntityCreeper['Creeper'/278, l='MpServer', x=-64.31, y=69.00, z=-38.47], EntityBat['Bat'/277, l='MpServer', x=-73.72, y=53.91, z=-24.07], EntitySheep['Sheep'/283, l='MpServer', x=-67.97, y=102.00, z=-3.03], EntitySkeleton['Skeleton'/281, l='MpServer', x=-63.31, y=66.00, z=-39.38], EntityZombie['Zombie'/280, l='MpServer', x=-64.50, y=77.00, z=-37.50], EntityOtherPlayerMP['teemboh1662'/219, l='MpServer', x=2.81, y=118.78, z=30.75], EntitySheep['Sheep'/284, l='MpServer', x=-64.50, y=103.00, z=46.94], EntityZombie['Zombie'/25, l='MpServer', x=-74.50, y=43.00, z=77.69], EntityBat['Bat'/27, l='MpServer', x=-68.53, y=47.67, z=66.66], EntitySpider['Spider'/26, l='MpServer', x=-73.19, y=43.00, z=76.00], EntityCreeper['Creeper'/28, l='MpServer', x=-67.50, y=51.00, z=68.50], EntityChicken['Chicken'/31, l='MpServer', x=-69.44, y=71.00, z=106.41], EntityChicken['Chicken'/34, l='MpServer', x=-76.66, y=71.00, z=110.59], EntityChicken['Chicken'/35, l='MpServer', x=-75.59, y=64.00, z=115.44], EntitySheep['Sheep'/310, l='MpServer', x=-14.44, y=77.00, z=-19.66], EntityBat['Bat'/798, l='MpServer', x=24.13, y=36.73, z=109.53], EntitySeat['entity.Seat.name'/520, l='MpServer', x=36.40, y=75.67, z=-14.52], EntitySeat['entity.Seat.name'/521, l='MpServer', x=48.72, y=82.96, z=-12.63], EntityBat['Bat'/47, l='MpServer', x=-58.16, y=30.60, z=59.25], EntityBat['Bat'/51, l='MpServer', x=-57.13, y=35.04, z=68.31], EntityZombie['Zombie'/50, l='MpServer', x=-54.50, y=46.00, z=66.50], EntityCreeper['Creeper'/290, l='MpServer', x=-59.50, y=74.00, z=-37.50], EntityBat['Bat'/49, l='MpServer', x=-60.53, y=44.85, z=81.25], EntityChicken['Chicken'/291, l='MpServer', x=-60.31, y=112.00, z=-18.47], EntitySkeleton['Skeleton'/48, l='MpServer', x=-56.94, y=46.00, z=84.68], EntityZombie['Zombie'/292, l='MpServer', x=-63.50, y=80.00, z=-10.50], EntityCreeper['Creeper'/55, l='MpServer', x=-55.30, y=47.00, z=84.30], EntitySheep['Sheep'/293, l='MpServer', x=-50.53, y=107.00, z=6.13], EntitySkeleton['Skeleton'/54, l='MpServer', x=-59.37, y=44.47, z=73.45], EntityZombie['Zombie'/53, l='MpServer', x=-56.55, y=46.25, z=85.50], EntityZombie['Zombie'/294, l='MpServer', x=-63.25, y=42.02, z=38.22], EntityZombie['Zombie'/52, l='MpServer', x=-56.31, y=46.00, z=83.88], EntityZombie['Zombie'/295, l='MpServer', x=-50.50, y=46.00, z=58.50], EntitySkeleton['Skeleton'/296, l='MpServer', x=-42.94, y=46.00, z=58.53], EntityChicken['Chicken'/58, l='MpServer', x=-56.53, y=64.00, z=113.53], EntityBat['Bat'/297, l='MpServer', x=-56.64, y=46.65, z=65.57], EntityBat['Bat'/298, l='MpServer', x=-55.81, y=46.18, z=58.51], EntitySkeleton['Skeleton'/56, l='MpServer', x=-60.53, y=46.00, z=80.22], EntitySheep['Sheep'/299, l='MpServer', x=-55.38, y=101.00, z=52.86], EntityBat['Bat'/779, l='MpServer', x=73.78, y=59.67, z=50.63], EntityChicken['Chicken'/61, l='MpServer', x=-51.47, y=65.00, z=112.53], EntityPlane['entity.Plane.name'/342, l='MpServer', x=48.51, y=83.23, z=-12.54], EntityChicken['Chicken'/69, l='MpServer', x=-47.59, y=66.00, z=108.63], EntityChicken['Chicken'/70, l='MpServer', x=-39.47, y=71.00, z=117.59], EntitySkeleton['Skeleton'/341, l='MpServer', x=50.47, y=69.00, z=-17.94], EntityBat['Bat'/340, l='MpServer', x=51.00, y=45.00, z=-37.93], EntityChicken['Chicken'/71, l='MpServer', x=-38.56, y=65.00, z=113.47], EntityPlane['entity.Plane.name'/338, l='MpServer', x=36.38, y=75.92, z=-14.52], EntityZombie['Zombie'/66, l='MpServer', x=-44.50, y=39.00, z=75.50], EntitySkeleton['Skeleton'/337, l='MpServer', x=45.34, y=48.00, z=-14.45], EntityZombie['Zombie'/67, l='MpServer', x=-43.50, y=82.00, z=64.50], EntitySpider['Spider'/336, l='MpServer', x=44.34, y=49.18, z=-15.56], EntityCreeper['Creeper'/346, l='MpServer', x=69.50, y=72.00, z=-17.50], EntityChicken['Chicken'/73, l='MpServer', x=-37.41, y=65.00, z=108.63], EntitySheep['Sheep'/345, l='MpServer', x=77.13, y=75.00, z=-36.94], EntityCreeper['Creeper'/334, l='MpServer', x=30.45, y=74.00, z=-27.50], EntityChicken['Chicken'/93, l='MpServer', x=-14.66, y=66.00, z=106.56], EntitySpider['Spider'/335, l='MpServer', x=44.50, y=68.00, z=-19.84], EntitySheep['Sheep'/92, l='MpServer', x=-23.09, y=77.00, z=72.09], EntitySkeleton['Skeleton'/332, l='MpServer', x=44.31, y=48.00, z=-18.69], EntityChicken['Chicken'/94, l='MpServer', x=-22.41, y=67.00, z=115.59], EntitySheep['Sheep'/333, l='MpServer', x=46.53, y=71.00, z=-29.47], EntitySkeleton['Skeleton'/331, l='MpServer', x=44.50, y=45.00, z=-27.13], EntitySheep['Sheep'/91, l='MpServer', x=-25.97, y=76.00, z=72.53], EntitySkeleton['Skeleton'/329, l='MpServer', x=24.50, y=75.00, z=-20.50], EntitySheep['Sheep'/90, l='MpServer', x=-27.28, y=76.00, z=72.84], EntitySheep['Sheep'/110, l='MpServer', x=-10.31, y=84.00, z=81.50], EntityChicken['Chicken'/111, l='MpServer', x=-8.47, y=68.00, z=119.44], EntityBat['Bat'/119, l='MpServer', x=17.91, y=24.26, z=62.94], EntityBat['Bat'/120, l='MpServer', x=17.72, y=30.92, z=90.38], EntityCreeper['Creeper'/137, l='MpServer', x=45.06, y=41.00, z=97.63], EntityZombie['Zombie'/136, l='MpServer', x=44.69, y=41.00, z=96.84], EntityZombie['Zombie'/135, l='MpServer', x=28.47, y=38.06, z=101.31], EntitySquid['Squid'/147, l='MpServer', x=58.34, y=58.94, z=94.69], EntitySquid['Squid'/148, l='MpServer', x=53.72, y=56.81, z=98.50], EntityCreeper['Creeper'/171, l='MpServer', x=-19.50, y=26.00, z=42.50], EntitySheep['Sheep'/170, l='MpServer', x=-28.41, y=105.00, z=31.53], EntityCreeper['Creeper'/169, l='MpServer', x=-16.09, y=25.00, z=30.72], EntityCreeper['Creeper'/168, l='MpServer', x=-13.91, y=26.00, z=34.16], EntityCreeper['Creeper'/175, l='MpServer', x=-15.31, y=25.00, z=31.59], EntitySheep['Sheep'/174, l='MpServer', x=-12.84, y=94.00, z=12.28], EntityBat['Bat'/173, l='MpServer', x=-23.00, y=25.85, z=55.50], EntityBat['Bat'/172, l='MpServer', x=-13.59, y=27.02, z=57.78], EntitySheep['Sheep'/167, l='MpServer', x=-24.56, y=79.00, z=0.41], EntityCreeper['Creeper'/166, l='MpServer', x=-45.09, y=46.00, z=59.78], EntityZombie['Zombie'/165, l='MpServer', x=-42.50, y=28.00, z=58.50], EntitySheep['Sheep'/164, l='MpServer', x=-45.09, y=111.00, z=25.03], EntityCreeper['Creeper'/186, l='MpServer', x=25.05, y=49.00, z=8.50], EntityCreeper['Creeper'/187, l='MpServer', x=40.59, y=49.00, z=13.00], EntitySkeleton['Skeleton'/184, l='MpServer', x=1.69, y=63.00, z=55.91], EntitySkeleton['Skeleton'/185, l='MpServer', x=1.28, y=63.00, z=54.97], EntityCreeper['Creeper'/190, l='MpServer', x=42.50, y=49.00, z=16.50], EntityZombie['Zombie'/191, l='MpServer', x=40.50, y=38.00, z=42.50], EntityCreeper['Creeper'/188, l='MpServer', x=35.31, y=49.00, z=13.69], EntityCreeper['Creeper'/189, l='MpServer', x=44.50, y=48.00, z=16.50], EntityBat['Bat'/178, l='MpServer', x=-15.50, y=26.07, z=31.31], EntityCreeper['Creeper'/179, l='MpServer', x=-1.59, y=104.00, z=60.00], EntitySheep['Sheep'/176, l='MpServer', x=-13.50, y=110.00, z=20.53], EntityCreeper['Creeper'/177, l='MpServer', x=-15.50, y=26.00, z=44.50], EntityBat['Bat'/183, l='MpServer', x=17.50, y=21.85, z=69.75], EntityAAGun['entity.AAGun.name'/180, l='MpServer', x=-5.50, y=118.00, z=48.50], EntityPlane['entity.Plane.name'/181, l='MpServer', x=0.28, y=119.22, z=33.04], EntityCreeper['Creeper'/205, l='MpServer', x=62.50, y=43.00, z=33.50], EntityCreeper['Creeper'/204, l='MpServer', x=59.50, y=43.00, z=23.50], EntityEnderman['Enderman'/207, l='MpServer', x=59.31, y=43.00, z=33.06], EntityCreeper['Creeper'/206, l='MpServer', x=58.50, y=44.00, z=36.50], EntityCreeper['Creeper'/201, l='MpServer', x=62.50, y=43.00, z=29.50], EntityZombie['Zombie'/200, l='MpServer', x=55.06, y=41.00, z=9.59], EntityCreeper['Creeper'/203, l='MpServer', x=59.50, y=43.00, z=20.50], EntityCreeper['Creeper'/202, l='MpServer', x=63.50, y=43.00, z=31.50], EntityCreeper['Creeper'/197, l='MpServer', x=54.03, y=41.00, z=10.13], EntityCreeper['Creeper'/738, l='MpServer', x=56.50, y=49.00, z=-18.50], EntitySpider['Spider'/196, l='MpServer', x=38.09, y=52.00, z=59.41], EntityZombie['Zombie'/199, l='MpServer', x=56.41, y=40.00, z=6.00], EntityCreeper['Creeper'/198, l='MpServer', x=53.50, y=41.00, z=11.50], EntityBat['Bat'/193, l='MpServer', x=54.53, y=38.14, z=36.00], EntityZombie['Zombie'/192, l='MpServer', x=40.50, y=37.00, z=40.50], EntityCreeper['Creeper'/195, l='MpServer', x=44.50, y=45.00, z=48.50], EntityBat['Bat'/194, l='MpServer', x=42.72, y=38.00, z=39.28], EntityCreeper['Creeper'/216, l='MpServer', x=80.00, y=54.00, z=44.56], EntitySkeleton['Skeleton'/217, l='MpServer', x=83.50, y=57.00, z=31.50], EntitySeat['entity.Seat.name'/218, l='MpServer', x=0.06, y=118.95, z=32.99], EntityOtherPlayerMP['teemboh1662'/219, l='MpServer', x=2.81, y=118.78, z=30.75], EntityZombie['Zombie'/212, l='MpServer', x=74.50, y=43.00, z=33.31], EntitySkeleton['Skeleton'/213, l='MpServer', x=73.16, y=43.00, z=36.13], EntitySkeleton['Skeleton'/214, l='MpServer', x=74.50, y=43.00, z=34.25], EntityZombie['Zombie'/215, l='MpServer', x=76.47, y=58.00, z=32.97], EntityCreeper['Creeper'/208, l='MpServer', x=63.63, y=59.00, z=44.47], EntityCreeper['Creeper'/209, l='MpServer', x=56.50, y=67.00, z=39.50], EntityCreeper['Creeper'/210, l='MpServer', x=64.50, y=38.00, z=20.50], EntityZombie['Zombie'/211, l='MpServer', x=75.50, y=43.00, z=35.50]]
	Retry entities: 0 total; []
	Server brand: fml,forge
	Server type: Non-integrated multiplayer server
Stacktrace:
	at net.minecraft.client.multiplayer.WorldClient.func_72914_a(WorldClient.java:440)
	at net.minecraft.client.Minecraft.func_71396_d(Minecraft.java:2298)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:844)
	at net.minecraft.client.main.Main.main(SourceFile:101)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:57)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:18)

-- System Details --
Details:
	Minecraft Version: 1.6.2
	Operating System: Windows 8 (amd64) version 6.2
	Java Version: 1.7.0_25, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 199042136 bytes (189 MB) / 482213888 bytes (459 MB) up to 954466304 bytes (910 MB)
	JVM Flags: 2 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx1G
	AABB Pool Size: 19269 (1079064 bytes; 1 MB) allocated, 1644 (92064 bytes; 0 MB) used
	Suspicious classes: FML and Forge are installed
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	FML: MCP v8.04 FML v6.2.35.804 Minecraft Forge 9.10.0.804 4 mods loaded, 4 mods active
	mcp{8.04} [Minecraft Coder Pack] (minecraft.jar) Unloaded->Constructed->Pre-initialized->Initialized->Post-initialized->Available
	FML{6.2.35.804} [Forge Mod Loader] (coremods) Unloaded->Constructed->Pre-initialized->Initialized->Post-initialized->Available
	Forge{9.10.0.804} [Minecraft Forge] (coremods) Unloaded->Constructed->Pre-initialized->Initialized->Post-initialized->Available
	FlansMod{2.4} [Flans Mod] (FlansMod-2.4.jar) Unloaded->Constructed->Pre-initialized->Initialized->Post-initialized->Available
	Launched Version: 1.6.2-Forge9.10.0.804
	LWJGL: 2.9.0
	OpenGL: GeForce GTX 460/PCIe/SSE2 GL version 4.3.0, NVIDIA Corporation
	Is Modded: Definitely; Client brand changed to 'fml,forge'
	Type: Client (map_client.txt)
	Resource Pack: Default
	Current Language: English (US)
	Profiler Position: N/A (disabled)
	Vec3 Pool Size: 3912 (219072 bytes; 0 MB) allocated, 480 (26880 bytes; 0 MB) used
