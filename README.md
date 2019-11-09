[![official JetBrains project](https://jb.gg/badges/official.svg)](https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub)
[![GitHub license](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg?style=flat)](https://www.apache.org/licenses/LICENSE-2.0)

# Kotlin Multiplafrorm projects: Sharing code between iOS, Android, and JVM Web Server (Ktor)

![screens](https://github.com/dmitrish/kinsight-multiplatform/blob/master/Screen%20Shot%202019-11-07%20at%209.06.33%20PM.png)

Switching server between thee possible builds: google app angine, netty, and netty with fatjar - settings.gradle:
![Switching server between google app engine and netty builds](https://github.com/dmitrish/kinsight-multiplatform/blob/master/settingsgradle.png)

If you want to run the google appengine locally, remember to change the engine path to your path!

![appengine path](https://github.com/dmitrish/kinsight-multiplatform/blob/master/googleappenginepath.png)

To run appengine locally, execute this gradle task

![appengine run task](https://github.com/dmitrish/kinsight-multiplatform/blob/master/googleappenginerun.png)


Note - if you want websockets enabled, you need to run one of the netty builds (regular netty or fatjar netty). Change settings.gradle as described above and execute this gradle task for the regular netty build:

![netty run task](https://github.com/dmitrish/kinsight-multiplatform/blob/master/nettyrun.png)



