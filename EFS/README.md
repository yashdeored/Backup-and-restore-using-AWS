So In this project I will create and show you a EFS backup plan and restore

We will start by creating a on-demand backup first where efs file will be retained for 7 days.

Start by going to 
<h3>

  ```
  Settings -> Configure resources
```

</h3>

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/14a98d1b-ae8f-43a2-8f0a-caee80f413ae)

<h3>

  ```
  EFS -> toggle the switch to enable EFS that will be protected by Backup Vault.
```

</h3>

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/c7a89a38-8b43-42f8-b297-e7e26f135cdf)

<h3>

  ```
  Dashboard -> Create on-demand backup
```

</h3>

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/3ae23ddf-1bb3-4425-aaa5-5b34da87c327)

<h3>

  ```
  Dashboard -> Create on-demand backup
```

</h3>

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/1a4a06ef-2c9b-4189-8b2f-eccfeb5ddac0)

<h3> We then are going to choose EFS from the resource type and I have already created a EFS so I am goona choose that. Also the reteion period for it will be choosen as 7 days which means for hamy days we choose to keep that data as Backup. 
Backup can be sent to cold storage so that the cost become lower but for that we need to keep the cold retention period of 90 days or above + the reteion date of warm storage. 
Example, you need to keep your data for 100 days so in order to save cost what you can do is keep the data in cold storage for 99 days + warm storage for 1 day or as you like.</h3>

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/f28705d3-84f5-43aa-b0ea-1cc41b4a90a1)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/7fe1726b-bb55-4494-a267-c56bd950e393)

<h3> End result should be as follows: </h3>

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/3cd3b125-0924-4c00-a9f4-628b1c4536f1)

<h1> Creating Backup Plan </h1>

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/81dfee83-6ae4-4f67-8631-1ba20858bb58)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/8abd61b2-6421-48b8-b5fe-22cde895d540)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/594d78a2-997c-44b8-adbd-0f357a0f2c3a)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/d876220b-1d72-4b9a-a5be-e07067153e18)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/f9d33516-00d5-43f0-a4bb-30ada72d1738)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/900fa2ee-24b6-4371-8cfe-daf04cddbba2)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/d9c64ff8-f798-4d39-b481-54c08b162d1e)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/ee0aeb35-fd33-40ec-ac3a-46d9c846482f)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/dabe4e44-e689-4ffd-93bc-0ae425ed2263)

![image](https://github.com/yashdeored/Backup-and-restore-using-AWS/assets/152061059/2419a410-cc5d-43dd-94b9-5d684914d766)




