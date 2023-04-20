Place holder file to capture the requirements for the virtio net device for features for upcoming 1.3 and 1.4 specification time frame.

Template:
# requirement_id: one line subject
Short description:\
Description of the requirment.\
Links:\
Link to spec/kernel interface/other material.

Example:
# 1. Support virtio net driver to query device counters

## Description:
### 1.1 A virtio net driver needs the ability to query device counters.
This includes:
1. packet drop counters due to lack of buffers
2. packet drop counters due to packets shorter than mtu length, 
3. packet counters based on specific byte sizes.
4. applicable tx counters

### 1.2 Counters to be 64-bit width.
### 1.3 Ability to query per vq counter by specifying the vq index
### 1.4 Ability to query the counter via control vq
