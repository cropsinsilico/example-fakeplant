# Fake Plant Example

This repository contains the model source and input data for the "fake plant" model for use with the Crops-in-Silico [web UI](https://www.cis.ndslabs.org) and [cisrun](https://github.com/cropsinsilico/cis_interface) command-line utility.

To use this example, create a Crops-in-Silico workspace directory on your local system. For example:
```
mkdir workspace
```

Clone this repository into the workspace:
```
cd workspace
git clone https://github.com/cropsinsilico/example-fakeplant 
```

Open a browser and access the web UI at http://www.cis.ndslabs.org/
* Load the "Fake plant" example graph
* Save the graph to disk in the above `workspace` directory
* `cisrun fakeplant.yml`

