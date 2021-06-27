# How To Guides

**Page Topics:**  

* [How to open and close a firewall port on Windows](#how-to-open-and-close-a-firewall-port-on-windows)
* [How to change a cars oil](#how-to-change-a-cars-oil)

## How to open and close a firewall port on Windows

Windows firewall at it's core, is designed to protect information on your computor against malicuous attacks on networks such as your Internet.

You can manually configure the **Firewall's communication rules** to block or allow specific server access to improve security or perform functions such as increasing the compatibility with VPNs and other software. in order to do this you will need to add a specific **Windows Firewall rule** to open or close the relevant port. 

> It is always good to research the safety risks involved before opening or closing a specific port.

### How to open a port in Windows 10

1. **Open the Windows Firewall app in Windows 10**

    Select the **Windows Start** button and type **“Windows Defender Firewall”**. Choose the top **Control Panel** option.

    ![Open Windows Firewall](/projects/images/first_step.png){: .left_small_picture}

2. **Open the advanced Firewall settings**

    In the left side-bar click on  **“Advanced settings”**.

    ![Advanced Firewall Setting](/projects/images/2.png){:class="img-responsive"}

3. **Select the ‘Inbound Rules’**. 

    Click **‘Inbound Rules’** on top, in the left side navigation bar.

    ![Advanced Firewall Setting](/projects/images/3.png){:class="img-responsive"}

4. **Add a new Rule***

    Press on the **New Rule** on top of the right side navigation bar.

    ![Add a new rule](/projects/images/4.png){:class="img-responsive"}

5. **Select the Rule Type** 

    Click on **Port** and select **Next**.

    ![Select rule type](/projects/images/5.png){:class="img-responsive"}

6. **Choose the Protocol and specific Port**

    Choose the **port** you want to open and select *Next*.

    ![Choose Protocl and Port](/projects/images/6.png){:class="img-responsive"}

    > It is important to match the specific **TCP, UDP** and **Port** details, accoding to the instructions of the software or server you want to access.

7. **Specify the Action**

    Select **“Allow the connection”** to open the port, then click on **Next**.

    ![Specify the Action](/projects/images/7.png){:class="img-responsive"}

8. **Select the profiles to which the rules apply**
    
    The profiles section is very important in order to maintain Network Security while these ports are open. If you want to open the port at the office, then select **Domain**, **Private** is ideal for when your laptop is connected at a more secure environment, like your home. **Public** will apply the rule to public shared networks such as when you are working at a local coffee shop. Select **Next** when you are done.

    ![Select the profile](/projects/images/8.png){:class="img-responsive"}

9.  **Name and Describe your rule**

    Be as descriptive as possible so that you will be able to find it easily. (Perhaps enter the reason in the **description box** for why you have opened this specific port). Click **Finish** to complete the process.

    ![Name and Describe rule](/projects/images/9.png){:class="img-responsive"}

10. **Confirm that the Rule is Enabled**

    When you access the main **Windows Defender Firewall** window, you will see your new rule at the top of the **Inbound Rules** list. The **“Profile”** column will show the type of network it’s allowed on. The **“Action”** column confirms that the **rule** is enabled (or disabled).

    ![Confirm the rule](/projects/images/10.png){:class="img-responsive"}

11. **Double Check that the right Windows 10 port is open**

    Use the scroll bar at the bottom of the **Windows Defender Firewall** window to scroll to the right until you see the **Protocol** and **Local Port** columns. They will confirm the specific port you have opened.

    ![Double Check](/projects/images/11.png){:class="img-responsive"}

    > Opening the wrong port could increase the security risk for your computor or cause connection issues with other servers, programs or networks.


### How to Close a Port in Windows 10 to Maintain Security

1. Select the **Windows Start** button and type **“Windows Defender Firewall”**. Choose the top **Control Panel** option.

2. Navigate to **Advance Settings** and click on **Inbound Rule**

3. Click on **“New Rule”** -> **Port** -> make sure that **TCP** is selected.

4. Specifiy the port details.

5. Select **“Allow the Connection”** and **Next**.

6. Make sure that **Domain**, **Private** and **Public** are ticked.

7. Add your preferred **Name and Description** then click on **Finish**






The main component of a Deployment Model in RapidDeploy is called the Project Orchestration. This is a series of target neutral steps that can run on any target server to deploy and/or configure a set of resources. A model can consist of multiple sub models. You access the Orchestration canvas by clicking on the ‘Projects’ icon in the icons panel at the top of any page or going to ‘Menu’ -> ‘Resources’ -> ‘Projects’ -> [Selected Project]. The orchestration Map canvas tab is the default tab when you edit a project.

 how to close a port to maintain security.



Open the Windows Firewall app in Windows 10

Press the Start button and type “Windows Defender Firewall”. Click the top result to open it.

## How to change a cars oil
