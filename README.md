# datafusion_cdap_action_plugin
Complete example project to create a custom Google cloud datafusion (CDAP) action plugin. Sourced and adapted from the documentation where there is no quickstart project.

## Action Plugin
An Action plugin runs arbitrary logic at the start or end of a batch data pipeline.

In order to implement an Action plugin, you extend the Action class. Only one method is required to be implemented: run()

### Methods
run(): Used to implement the functionality of the plugin.

configurePipeline(): Used to perform any validation on the application configuration that is required by this plugin or to create any datasets if the fieldName for a dataset is not a macro.
