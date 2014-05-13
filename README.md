Unity3D_DogeCoin
================

Summary:

This is a plugin for Unity3D games to have a donation button that accepts Dogecoin

How to Use: 

  There are two ways this can be used
  1. Make your own button and have it call dogecoinDonation.donateDogeCoin(int amount, string key); You MUST pass it a donation amount and a dogecoin wallet key.
  2. Place dogecoinDonation script on any gameobject. Change the key to your dogecoin wallet key, change the donation Amount to your desired number, and change the placement to your desired location.


Questions: 

Q: If I call the static method and make my own button, where does the script need to be in my project?
A: The script can be anywhere you want it to be. It doesn't have to exist in the scene either. The most common place is in a folder called "Plugins"

