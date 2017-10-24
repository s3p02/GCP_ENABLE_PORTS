# GCP_ENABLE_PORTS

# Step 1: Click on your instance

<kbd>
  <img src="/0.png">
</kbd>

# Step 2: Click on EDIT

<kbd>
  <img src="/0_edit.JPG">
</kbd>

# Step 3: Under Network Interfaces,edit default

<kbd>
  <img src="/1_network.JPG">
</kbd>

# Step 4: Click default under Network

<kbd>
  <img src="/2_default.JPG">
</kbd>

# Step 5: Add Firewall rule

<kbd>
  <img src="/3_firewall.JPG">
</kbd>

# Step 6: Create a Firewall rule

# Name your firewall to something you can identify, set Targets to 'All instances in network', and set Source IP ranges to '0.0.0.0/0'

<kbd>
  <img src="/5_create1.JPG">
</kbd>

# Step 7: Click on your instance

#Specified protocols and ports to 'tcp:5000' as we want to enable port 5000 for digits

<kbd>
  <img src="/6_create2.JPG">
</kbd>

# Similarly follow the same procedure from the begining to enable port 8888 for jupyter notebook.

