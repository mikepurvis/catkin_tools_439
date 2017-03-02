Simple demonstration of [catkin_tools#439](https://github.com/catkin/catkin_tools/issues/439).
From the root of this repo, invoke a build with catkin_tools 0.4.4:

```
$ catkin build
--------------------------------------------------------------
Profile:                     default
Extending:             [env] /opt/ros/indigo
Workspace:                   /Users/mikepurvis/test_ws
--------------------------------------------------------------
Source Space:       [exists] /Users/mikepurvis/test_ws/src
Log Space:         [missing] /Users/mikepurvis/test_ws/logs
Build Space:        [exists] /Users/mikepurvis/test_ws/build
Devel Space:        [exists] /Users/mikepurvis/test_ws/devel
Install Space:      [unused] /Users/mikepurvis/test_ws/install
DESTDIR:            [unused] None
--------------------------------------------------------------
Devel Space Layout:          linked
Install Space Layout:        None
--------------------------------------------------------------
Additional CMake Args:       None
Additional Make Args:        None
Additional catkin Make Args: None
Internal Make Job Server:    True
Cache Job Environments:      False
--------------------------------------------------------------
Whitelisted Packages:        None
Blacklisted Packages:        None
--------------------------------------------------------------
Workspace configuration appears valid.
--------------------------------------------------------------
[build] Found '2' packages in 0.0 seconds.                                                                                                      
[build] Package table is up to date.                                                                                                            
```

The build hangs here indefinitely.
