
### automatic module

* `commons-lang3-3.5.jar` used as automatic module
* placed on module-path as `3rdparty/commons.lang3.jar`
* see `src/net.codetojoy.service/module-info.java` [here](https://github.com/codetojoy/easter_eggs_for_java_9/blob/master/egg_05a_Automatic_Module/src/net.codetojoy.service/module-info.java)

### Execution Steps

* `./compile.sh`
* `./run_UserService.sh`

optionally, describe modules, run another module:

* `list_net.codetojoy.db.sh`
* `list_net.codetojoy.service.sh`
* `./run_UserDao.sh`
