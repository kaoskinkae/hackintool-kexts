# Adding kext repositories in Hackintool


![AppIcon](https://github.com/user-attachments/assets/7913aaf2-6043-4b42-a2be-e70ba79716f4)



There is a simple way to add kext repositories in Hackintool. For this, we need to locate the Releases of the kext or kexts that we want to add so that it can be added in "kexts.plist"

## Locate the kext to add

We locate the www of the kext or kext in question and locate or copy the Releases before where all the available versions of the kext or kexts are located.

https://github.com/aluveitie/RadeonSensor

## Find where we should add the kext download information in Hackintool

Now we go to the Hackintool application, we position ourselves on it, right click "show package contents" we go to "hackintool/Contents/Resources/Kexts" We locate the kexts.plist and open it PlistEdit Pro or any program that we have for that purpose

![Captura de pantalla 2025-04-25 a las 10 07 50](https://github.com/user-attachments/assets/18687578-4a1e-4605-807c-db443466c4b9)



We select the last entry and select "duplicate."
Now it's time to adapt this duplicate to the kext in the RadeonSensor example.

_______________________________________________________________________________________

Description: Kext and Gadget to show Radeon GPU temperature on macOS

Name: RadeonSensors

ProjectUrl: https://github.com/aluveitie/RadeonSensor

Type: kext

_______________________________________________________________________________________

![Captura de pantalla 2025-04-25 a las 10 21 17](https://github.com/user-attachments/assets/e0f654a9-66a8-4a05-8be4-062fa4d17e2a)

There are other variants of kext download indication that should be looked at within all the kext that Hackintool has added. This method is only for this kext.

## Check that the kext was added correctly

Once the new Hackintool line is saved in kexts.plist, we reopen the application and in the kext section it will appear reflected in added kext

We can do this with any kext that we know has a corresponding Resource and is not on the Hackintool list.

![Captura de pantalla 2025-04-25 a las 10 06 57](https://github.com/user-attachments/assets/ad687e11-8a47-44b3-bae4-2a7d4a1a1918)

Now we just have to wait for the kext in question to include a new version of the kext so that it becomes available for download.



