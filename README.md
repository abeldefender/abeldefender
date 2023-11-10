---- Minecraft Crash Report ----
// You're mean.

Time: 2023-11-10 00:55:12
Description: Exception in server tick loop

java.lang.NoSuchMethodError: 'net.minecraft.world.level.block.state.BlockState com.ldtteam.structurize.blueprints.v1.Blueprint.getBlockState(net.minecraft.core.BlockPos)'
	at com.minecolonies.coremod.placementhandlers.main.SurvivalHandler.handle(SurvivalHandler.java:109) ~[minecolonies-1.20.1-1.1.240-RELEASE.jar%23189!/:1.20.1-1.1.240-RELEASE] {re:classloading}
	at com.ldtteam.structurize.storage.BlueprintPlacementHandling.process(BlueprintPlacementHandling.java:76) ~[structurize-1.20.1-1.0.662-BETA.jar%23196!/:1.20.1-1.0.662-BETA] {re:classloading}
	at com.ldtteam.structurize.storage.BlueprintPlacementHandling.lambda$handlePlacement$0(BlueprintPlacementHandling.java:55) ~[structurize-1.20.1-1.0.662-BETA.jar%23196!/:1.20.1-1.0.662-BETA] {re:classloading}
	at com.ldtteam.structurize.storage.ServerFutureProcessor.onWorldTick(ServerFutureProcessor.java:73) ~[structurize-1.20.1-1.0.662-BETA.jar%23196!/:1.20.1-1.0.662-BETA] {re:classloading}
	at com.ldtteam.structurize.storage.__ServerFutureProcessor_onWorldTick_LevelTickEvent.invoke(.dynamic) ~[structurize-1.20.1-1.0.662-BETA.jar%23196!/:1.20.1-1.0.662-BETA] {re:classloading,pl:eventbus:B}
	at net.minecraftforge.eventbus.ASMEventHandler.invoke(ASMEventHandler.java:73) ~[eventbus-6.0.5.jar%2384!/:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:315) ~[eventbus-6.0.5.jar%2384!/:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:296) ~[eventbus-6.0.5.jar%2384!/:?] {}
	at net.minecraftforge.event.ForgeEventFactory.onPostLevelTick(ForgeEventFactory.java:930) ~[forge-1.20.1-47.2.4-universal.jar%23210!/:?] {re:classloading}
	at net.minecraft.server.MinecraftServer.m_5703_(MinecraftServer.java:899) ~[client-1.20.1-20230612.114412-srg.jar%23205!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:openpartiesandclaims:xaero_pac_minecraftserverclass,xf:fml:xaerominimap:xaero_minecraftserver,xf:fml:xaeroworldmap:xaero_wm_minecraftserver,re:classloading,pl:accesstransformer:B,xf:fml:openpartiesandclaims:xaero_pac_minecraftserverclass,xf:fml:xaerominimap:xaero_minecraftserver,xf:fml:xaeroworldmap:xaero_wm_minecraftserver,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.m_5705_(MinecraftServer.java:814) ~[client-1.20.1-20230612.114412-srg.jar%23205!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:openpartiesandclaims:xaero_pac_minecraftserverclass,xf:fml:xaerominimap:xaero_minecraftserver,xf:fml:xaeroworldmap:xaero_wm_minecraftserver,re:classloading,pl:accesstransformer:B,xf:fml:openpartiesandclaims:xaero_pac_minecraftserverclass,xf:fml:xaerominimap:xaero_minecraftserver,xf:fml:xaeroworldmap:xaero_wm_minecraftserver,pl:mixin:A}
	at net.minecraft.client.server.IntegratedServer.m_5705_(IntegratedServer.java:89) ~[client-1.20.1-20230612.114412-srg.jar%23205!/:?] {re:classloading,xf:fml:openpartiesandclaims:xaero_pac_integratedserver_tickpaused,pl:runtimedistcleaner:A}
	at net.minecraft.server.MinecraftServer.m_130011_(MinecraftServer.java:661) ~[client-1.20.1-20230612.114412-srg.jar%23205!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:openpartiesandclaims:xaero_pac_minecraftserverclass,xf:fml:xaerominimap:xaero_minecraftserver,xf:fml:xaeroworldmap:xaero_wm_minecraftserver,re:classloading,pl:accesstransformer:B,xf:fml:openpartiesandclaims:xaero_pac_minecraftserverclass,xf:fml:xaerominimap:xaero_minecraftserver,xf:fml:xaeroworldmap:xaero_wm_minecraftserver,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.m_206580_(MinecraftServer.java:251) ~[client-1.20.1-20230612.114412-srg.jar%23205!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:openpartiesandclaims:xaero_pac_minecraftserverclass,xf:fml:xaerominimap:xaero_minecraftserver,xf:fml:xaeroworldmap:xaero_wm_minecraftserver,re:classloading,pl:accesstransformer:B,xf:fml:openpartiesandclaims:xaero_pac_minecraftserverclass,xf:fml:xaerominimap:xaero_minecraftserver,xf:fml:xaeroworldmap:xaero_wm_minecraftserver,pl:mixin:A}
	at java.lang.Thread.run(Thread.java:833) ~[?:?] {}


