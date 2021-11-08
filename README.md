<h2>Clover 5142 EFI for Dell Latitude 5480 on Monterey (and Big sur)</h2>
![Screenshot](https://user-images.githubusercontent.com/93940095/140804252-1ce774ed-0c04-4dcb-904b-3f8194ef685a.png)
<h4> Important : this EFI is meant for Monterey, if you're willing to boot into Big Sur, please make sure you remove "BlutoothFixup.kext" from /EFI/Clover/Kexts/other, make sure you replace the "Airportitlwm.kext" with [This](https://github.com/OpenIntelWireless/itlwm/releases/download/v2.0.0/AirportItlwm_v2.0.0_stable_BigSur.kext.zip) in order for WiFi to work !</h4>
 <br>
<h4>My Specs</h4>
<ul>
 <li>Resolution : 1366x768</li>
 <li>CPU : i5 6300U</li>
 <li>iGPU : HD Graphics 520</li>
 <li>RAM : 2x8Gb SK Hynix 2400MHz DDR4 (runs at 2133MHz)</li>
 <li>Audio : Realtek ALC256</li>
 <li>SSD : Stock 256Gb Intel M.2 SATA III</li>
 ...
</ul>
<h6>What's not Working :</h6>
<ul>
 <li>Bluetooth detects other devices but can't maintain the connection (therefore, Airdrop too isn't working)</li>
 <li>SD Card Reader Not Tested but a kext for it is included</li>
 <li>Fan Control, Undected by 3rd party apps, but are working</li>
 <li>Brightness Keys (F11 and F12)</li>
</ul>
<h6>What's Working :</h6>
<ul>
  <li>HDMI with Audio</li>
  <li>Headphone Jack</li>
  <li>VGA</li>
  <li>Keyboard and Touchpad with Gestures</li>
  <li>and almost everything I can recall...</li>
</ul>
<br><br>
I was able to achieve this thanks to the help of Jake Lo from https://osxlatitude.com :-)
