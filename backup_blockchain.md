# see:
   [Profit Hunters Coin Masternodes---Backup your settings & blockchain](https://profithunterscoin.com/index.php?page=Masternode_backup)
   [Manual wallet installation](https://wiki.vericoin.info/index.php?title=Manual_wallet_installation)
   [SHIELD v2 -> v3 Upgrade Instructions](https://docs.shield.sh/miscguides/shield-v3-upgrade-instructions)

# Blockchain backup

Terminal
```
  $cd .PHC
  $cp txleveldb txleveldb-bkp
  $cp blk0001.dat blk0001-bkp.dat
  
  
 
```

### You may wish to delete residual data to save some space in your data folder.
These files and folders are safe to delete (take care not to delete anything else!):

1. the txleveldb folder and its contents
2. the database folder and its contents
3. the blk0001.dat file (NOT inside the blocks folder!)

### These files are safe to delete before the upgrade, but please don't delete them afterwards:
1. the peers.dat file
2. the db.log and debug.log files
