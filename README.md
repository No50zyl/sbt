# sbt
关于sbt的配置以及sbt在idea中的配置
安装完sbt后，进入conf，修改sbtconfig以及repo
复制sbtconfig内容到idea->setting->buildtools->sbt的vm parameters 并修改launcher为..../sbt/bin/sbt-launch
idea引入assembly时注意要对应sbt版本
