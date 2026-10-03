# Ancora-Education-Ucertify-Lab5
# Taking an Incremental Backup

> **Original Lab Source**
> This lab was available through:
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=2]

## Objective of the Lab
In this lab, you will learn to take an incremental backup. In an incremental backup, all files that have been changed since the last full or incremental backup will be backed up. During the incremental backup process, the archive bit for each file is cleared. To take an incremental backup, here's what you need to do.

## Instructions
1.Click the Start menu and open Windows Administrative Tools.

2.In the Administrative Tools window, in the right pane, scroll down, and double-click Windows Server Backup. 

3.In the wbadmin window, in the left pane, double-click Local Backup. 

4.In the right pane, under Actions, click Configure Performance Settings. 

5.In the Optimize Backup Performance dialog box, select the Custom radio button and from the Backup Option list, select Incremental backup for all the displayed volumes and click OK. 
>>An incremental backup usually takes the least amount of time and space to complete. In an organization that uses a full/incremental scheme, the full backup and each subsequent incremental backup must be restored. The incremental backups must be restored in order.

6.In the right pane, click Backup Once.

7.In the Backup Once Wizard window, perform the following steps:

  a.At the Backup Options step, click Next. 
  
  b.At the Select Backup Configuration step, select the Custom radio button and click Next. 
  
  c.At the Select Items for Backup step, click Add Items. 
  
  d.In the Select Items dialog box, double-click Local Disk (C):, scroll down, check the ip.txt checkbox, and then click OK. 
  
  e.Click Next twice. 
  
  f.At the Select Backup Destination step, from the Backup destination list, select New Volume (E:) and click Next. 
  
  g.At the Confirmation step, click Backup. 
  
  Note: Wait till the backup process completes. It may take up to 15 to 20 minutes. 
  
  h.At the Backup Progress step, when Status is displayed as Completed, click Close.

  ## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
