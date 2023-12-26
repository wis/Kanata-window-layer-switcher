# Kanata window layer switcher
Kanata window layer switcher is a TCP client for Kanata, it listenes for a LayerChange event, a LayerChange event with a specific layer name ("`window-layer-switch`"), and then it sends a ChangeLayer command to Kanata to switch to layer with the name of the active window's name.
