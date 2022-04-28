# Asrock-H510M-ITX-AC-Opencore-Big-Sur
PC build (SMBIOS: iMac 20,1)  
CPU: Core i3-10100  
RAM: Adata 8GB DDR4 2666 x2  
GPU: Sapphire Radeon HD 7770 1GB DDR5 (just to replace the iGPU - radpg=15)

# Previous Problems
Not sure why the other opencore builds for H510M ITX/AC will not work on mine, problems include:  
<ul>
  <li>[EB|#LOG:EXITBS:START (Fixed by disabling iGPU － no Sidecar, DRM on safari)</li>
  <li>_dlil_get_flowswitch_buffer_size: en0 9000 1500 - remove iGPU entry in DeviceProperties</li>
  <li>panic(cpu 6 caller 0xffff....): Non-monotomic time - update CpuTscSync</li>
</ul>

# Working
<ul>
  <li>Forked from nnhan0719</li>
  <li>WiFi and Bluetooth w/ BCM94360CS2 natively supported</li>
  <li>Audio</li>
  <li>Sleep, wake, shutdown</li>
  <li>Continuity, handoff, airplay audio, airdrop</li>
  <li>Ethernet</li>
</ul> 

# Not Working
<ul>
  <li>Sidecar, DRM in safari</li>
  </ul>
