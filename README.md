# Lilvmm Swig
LV2 Plugin Host for LuaJIT, Python  etc
 
```lua
require('lilv')
w = lilv.World()
w:load_all()
plugins = w:get_all_plugins()
print(plugins:size())
iter = plugins:begin()
plugin = plugins:get(iter)
print(plugin)
n = plugin:get_name()
print(n:as_string())
```
