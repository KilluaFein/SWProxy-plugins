## SWProxy Plugins
plugins for the SW Proxy

Each plugin have 2 files, a .py file with the actual plugin code and a .yapsy-plugin file with the plugin description. 
To install the plugins just drop the desired plugins  in the /plugins folder, copy and edit the .config file to the parent foolder and restart sw proxy.

### Full Logger
Dumps the contents of the requests and responses from/to com2us servers on a text file ("full_log_filename" from swproxy.config)

### Recruit Evaluator
This plugin will generate extra data when visiting friend. The extra data is intended to help with guild recruit evaluation.

### Run Logger
Will log runs and drops from Necro, Dragons, Giants, elemental halls and HoH. The outut filename is defined in the "log_runs_filename" parameter of swproxy.config  

### Summon Logger
Will log summons of any type of scroll, including social and crystal summon. Does not work with individual monster pieces (from SD). Is currently untested with LS and L&D pieces. The outut filename is defined in the "log_summon_filename" parameter of swproxy.config
