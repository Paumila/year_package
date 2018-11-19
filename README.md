# Year_package

Per poder contestar la pregunta 6 obrim la carpeta de usb_cam a través del terminal i obrim el arxiu usb_cam-test.launch per veure quins arguments conté

El process per poder obrir aquest arxiu es:

```pau@pau-LIFEBOOK-T904:~$ roscd usb_cam/```

```pau@pau-LIFEBOOK-T904:/opt/ros/melodic/share/usb_cam$ ls```

```cmake  launch  package.xml```

```pau@pau-LIFEBOOK-T904:/opt/ros/melodic/share/usb_cam$ cd launch/```

```pau@pau-LIFEBOOK-T904:/opt/ros/melodic/share/usb_cam/launch$ ls```

```usb_cam-test.launch```

```pau@pau-LIFEBOOK-T904:/opt/ros/melodic/share/usb_cam/launch$ atom usb_cam-test.launch```

Dins el arxiu no s'observa cap argument

Un exemple d'argument dins un arxiu .launch seria:

```<launch>```

  ```<!-- declare arg to be passed in -->```
  
  ```<arg name="hoge" />``` 

  ```<!-- read value of arg -->```
  
  ```<param name="param" value="$(arg hoge)"/>```
  
```</launch>```

Per tant la resposta a la pregunta Q6 es que no hi ha cap argument que utilitzi el arxius usb_cam-test.launch
