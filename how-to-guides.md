# "How-To" Guides

**Page Topics:**  

* [How to Open and Close a Firewall Port on Windows](#how-to-open-and-close-a-firewall-port-on-windows)
* [How to Change a Car's Oil](#how-to-change-a-cars-oil)

## How to Open and Close a Firewall Port on Windows 10

Windows Firewall at its core is designed to protect information on your computer against malicious attacks on networks such as your Internet.

You can manually configure the **Firewall's communication rules** to block or allow specific server access to improve security or perform functions such as increasing the compatibility with VPNs and other software. In order to do this, you will need to add a specific **Windows Firewall Rule** to open or close the relevant port. 

> It is always good to research the safety risks involved before opening or closing a specific port.

### How to open a port in Windows 10

1. **Open the Windows Firewall app in Windows 10**

    Select the **Windows Start** button and type **“Windows Defender Firewall”**. Choose the top **Control Panel** option.

    ![Open Windows Firewall](/projects/images/first_step.png){: .left_small_picture}

2. **Open the Advanced Firewall settings**

    In the left sidebar click on  **“Advanced settings”**.

    ![Advanced Firewall Setting](/projects/images/2.png){:class="img-responsive"}

3. **Select the ‘Inbound Rules’**. 

    Click **‘Inbound Rules’** on top, in the left side navigation bar.

    ![Advanced Firewall Setting](/projects/images/3.png){:class="img-responsive"}

4. **Add a new Rule**

    Press on the **New Rule** icon on top of the right-side navigation bar.

    ![Add a new rule](/projects/images/4.png){:class="img-responsive"}

5. **Select the Rule Type** 

    Click on **Port** and select **Next**.

    ![Select rule type](/projects/images/5.png){:class="img-responsive"}

6. **Choose the Protocol and specific Port**

    Choose the **port** you want to open and select **Next**.

    ![Choose Protocl and Port](/projects/images/6.png){:class="img-responsive"}

    > It is important to match the specific **TCP, UDP,** and **Port** details, according to the instructions of the software or server you want to access.

7. **Specify the Action**

    Select **“Allow the connection”** to open the port, then click on **Next**.

    ![Specify the Action](/projects/images/7.png){:class="img-responsive"}

8. **Select the Profiles to which the Rules apply**
    
    The profiles section is very important in order to maintain Network Security while these ports are open. If you want to open the port at the office, then select **Domain**. **Private** is ideal for when your laptop is connected to a network at a secure environment, like your home. **Public** will apply the rule to public shared networks such as when you are working at a local coffee shop. Select **Next** when you are done.

    ![Select the profile](/projects/images/8.png){:class="img-responsive"}

9.  **Name and Describe your rule**

    Be as descriptive as possible so that you will be able to find it easily. (Perhaps enter the reason in the **description box** for why you have opened this specific port). Click **Finish** to complete the process.

    ![Name and Describe rule](/projects/images/9.png){:class="img-responsive"}

10. **Confirm that the Rule is Enabled**

    When you access the main **Windows Defender Firewall** window, you will see your new rule at the top of the **Inbound Rules** list. The **“Profile”** column will show the type of network it’s allowed on. The **“Action”** column confirms that the **Rule** is enabled (or disabled).

    ![Confirm the rule](/projects/images/10.png){:class="img-responsive"}

11. **Double Check that the right Windows 10 Port is Open**

    Use the scroll bar at the bottom of the **Windows Defender Firewall** window to scroll to the right until you see the **Protocol** and **Local Port** columns. They will confirm the specific port you have opened.

    ![Double Check](/projects/images/11.png){:class="img-responsive"}

    > Opening the wrong port could increase the security risk for your computer or cause connection issues with other servers, programs, or networks.


### How to Close a Port in Windows 10 to Maintain Security

1. Select the **Windows Start** button and type **“Windows Defender Firewall”**. Choose the top **Control Panel** option.

2. Navigate to **Advanced Settings** -> **Inbound Rule**.

3. Click on **“New Rule”** -> **Port** -> make sure that **TCP** is selected -> **Next**.

4. Specify the port details -> **Next**

5. Select **“Block the Connection”** -> **Next**.

6. Make sure that **Domain**, **Private** and **Public** are ticked -> **Next**

7. Add your preferred **Name and Description** -> **Finish**.

_____________________________________________________

## How to Change a Car's Oil

Although the steps below are relevant to most car models, it is advised to check your car's manual for specific procedure guidance according to your vehicle model. 

To successfully perform the following procedure you will need:
- a new oil filter suitable for your specific vehicle model
- new, clean engine oil (check your oil cup's cap in the front part of the engine to see what kind of oil your vehicle requires)
- a new oil plug and seal suitable for your vehicle model
- some vehicle models might also need an oil filter socket, strap, or cup
- wrenge or socket and rachet
- drain pan
- funnel
- gloves
- some old rags
- jack and a jack stand


### Steps to Follow

1. **Check the Specifications** 

    First of all, it is important to check your car's manual for the oil filter specifications to make sure you buy the right oil filter and the correct amount of oil for your specific engine. 

2. **Safely Jack up your Car**

    Make sure to put your safety first by jacking up the car and using a jack stand (not only your jack) to secure your vehicle in the air.  Your car's manual should specify where to place the jack stand or the floor jack in order to lift your car safely.

    Use a hard, leveled, clean surface to park your car and jack it up.

3. **Remove the Plastic Cover**

    Open your car's bonnet to inspect which side the vehicle's engine is situated on (front wheel drives are usually on the passenger side and the gearbox on the opposite side). You will be working underneath the car, directly on the side of the engine. 
    
    If your car has a plastic cover underneath to cover the engine, you will need to remove this first. (Some cars have a separate hatch on the plastic cover to easily reach the oil filter and drain plug, in this case, you don't need to remove the plastic engine cover.)

4. **Drain the Oil**

    Search for the **drain plug** on the oil pan underneath the car on the engine's side and turn it counterclockwise to loosen the plug. 
    > Make sure that you are unscrewing the correct screw, double-check this in your car's manual. Unscrewing the wrong screw and draining the oil from your gearbox can be rather difficult to replace.

    Once allocated, remove it and allow the oil to drain out. This can take some time.

    Inspect the **oil plug** and the **seal** properly to ensure that it is still in a good enough condition to prevent an oil leak. If you see any damage or cracks on the seal, it is best to replace it.

    Now make sure to use a torque wrench to tighten the oil plug again by turning it clockwise. You can consult your car's manual for the correct torque specifications.

5. **Replace the Oil Filter**

    Locate the oil filter in your vehicle model, it can be underneath, in the front part of the engine but can also be situated in the rear of the engine or on the front side near the wheel valve. The most common location for an insert filter is at the top of the engine. 
    
    You get two types of filters:
    - **Canister or "Twist On" filter** -> *lubricate the seal of the new one before installing it*. After installing this type of filter, give it an extra quarter turn to ensure that it is properly in place.
    - **Cartridge filter** -> easy to replace, remove the old one and insert the new one.
    
    Remove the oil filter with the oil filter socket and replace it together with all **0-rings and double-check that the oil filter cap is tightened again to the specified torque**.

6. **Replace the Engine Oil**

    Remove the **dipstick** to remove any air from the engine

    Finally, you can fill up the engine with fresh, clean **engine oil**, be sure to fill the required amount through the **oil cap** at the top of the engine.
    > Do not spill any oil over the other engine parts.

    Once you have filled your engine with the required amount of oil, replace the oil cap's lid and check the oil dipstick - it should be slightly above the *MAX* symbol.

7. **Time to Start the Engine**

    Switch on your engine to make sure that the red oil pressure light on the dashboard comes on and then turns off after a few seconds.

    Start the engine and let it idle to refill the new oil filter with oil, you can switch it off after 15 seconds.

8. **Check the Dipstick**

    After switching your engine off, **wait 5 minutes** so that the oil can flow into the oil pan.
    Then check the dipstick, the oil level should now be between *Min* and *Max*.

    > Sometimes the oil level can be on the *Max* sign, double-check your car's manual to see what it should be on.

9. **Start the Engine Again**

    If the oil level is as specified, you can start your car again and let it idle for 10 minutes. Check that **no oil is leaking from the screw plug or filter**.

10. **Final step**
    
    Remove the jack stand and take your car for a short drive, make sure to lift your car again when you return to check for signs of oil leaking underneath the car from the oil filter or oil plug.

    You can replace the plastic engine cover if there are no leaks.

    Lastly, check the oil dipstick again to make sure that the oil level is correct.

### Conclusion

If you have questions about your specific oil filter, the amount of oil required according to your vehicle model, or the procedure, you can always call your local dealership for more advice, or visit your local auto parts store.  
