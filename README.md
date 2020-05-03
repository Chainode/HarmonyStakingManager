# Harmony Staking Manager

Harmony Staking Manager is a Telegram bot that serves both Harmony validators and stakers.<br/>
Harmony Staking Manager can be accessed here: https://t.me/HarmonyStakingMngBot

![image](https://user-images.githubusercontent.com/53407923/80927386-dd46ad80-8d9d-11ea-9760-ab490035624b.png)

The purpose of creating this bot was to provide the Harmony community with a high quality UX monitoring and alerting tool that works as a personal assistant in order to never miss crucial information related to the validator stats, staker stats and network status.

**Who can use this bot?**<br/>
Both stakers and validators can use this bot and choose which type of alerts or notifications they would like to receive.
![image](https://user-images.githubusercontent.com/53407923/80927403-f3546e00-8d9d-11ea-98c8-146f4a46e0bc.png)<br/><br/>


The Harmony Staking Manager menu is very intuitive and provides the following functionalities:<br/><br/>
**Validator Stats**<br/>
The Validator Stats part of the menu is relevant for the Harmony validators and in this section it is possible to add, remove and monitor your validators. You can add 1 or multiple validators, as shown below.<br/>
![image](https://user-images.githubusercontent.com/53407923/80927414-01a28a00-8d9e-11ea-9417-ff7207d76d81.png)<br/>


**Staker Stats**<br/>
The Staker Stats part of the menu is a section dedicated to all Harmony stakers/delegators. Stakers will only need to add their address and press again on “Staker Stats”. The software will then check to which validators the staker has delegated the ONE tokens and display a list of relevant parameters like validator status, commission rate, uptime and rewards.<br/>
![image](https://user-images.githubusercontent.com/53407923/80927429-11ba6980-8d9e-11ea-8787-8aabfe420111.png)<br/>


**Network Status**<br/>
Network Status is a feature that can be used by both validators and stakers and will display the health check of the network by showing the latest status of each shard.<br/>
![image](https://user-images.githubusercontent.com/53407923/80927436-1b43d180-8d9e-11ea-9e82-6e8658a6e03b.png)<br/>


**Notifications**<br/>
The “Notifications” section represents the most powerful part of the Staking Manager Bot and it currently provides the following features:<br/>

*Network Status Notifications*<br/>
In case one shard or multiple shards will have an issue, the user will be automatically notified if this alert is set as active.<br/>

*Validator Status Notifications*<br/>
If this feature will be activated the user will be notified about the election status of both manually added validators in the section “Validators Stats” and validators identified automatically in the section “Staker Stats”.<br/>

*Validator Uptime Notifications*<br/>
If this feature will be activated the user will be notified about the uptime change of both manually added validators in the section “Validators Stats” and validators identified automatically in the section “Staker Stats”.
Each user can define an uptime change threshold in the format xx.xx. The software will interpret this as a change in uptime of xx.xx % and will notify the user if one of the validators will increase or decrease in uptime by xx.xx %. Example: a user defines an uptime change threshold of 0.1. The Staking Manager tool will interpret this as 0.1% and if one of the validators will decrease or increase their uptime by 0.1%, then the user will be automatically notified.<br/>

*Validator Fee Notifications*<br/>
If this feature will be activated the user will be notified about the fee change of both manually added validators in the section “Validators Stats” and validators identified automatically in the section “Staker Stats”.<br/>

*Validator Delegation Notifications*<br/>
This feature is specially dedicated to validators. They can define a lower and upper margin for the amount of tokens delegated to them and will be notified if a certain amount of tokens were delegated to or removed from their validator. This type of notification will inform validators when they have to check and potentially expand or limit their validator capacity (for example by adding or removing a BLS key).<br/>

**UX (User Experience)**<br/>
When we designed the Harmony Staking Manager tool, we did it with the UX in the back of our minds. As we are already running validators on multiple blockchain protocols, including Harmony, we made use of our validator experience when deciding which parameters and notifications we wanted the tool to provide. We did this with both validators and stakers in mind and made sure to cater the most important information in the most efficient and user friendly way.<br/>
Each of the implemented notifications can be activated/deactivated individually, as it can be seen in the picture below. <br/>
![image](https://user-images.githubusercontent.com/53407923/80927442-272f9380-8d9e-11ea-826c-730c381d270f.png)

