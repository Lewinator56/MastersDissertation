# Dev Log
## 29-07-2022

### Disaster Strikes
- HDD died the day before I was doing my backup, EVERYTHING is gone, unable to recover the data.
- Honestly, This is terrible and ive not only lost work, but 2TB worth of data, to compound things, due to the lacking HDD, the google drive app decided to sync after the laptop booted without the HDD in (off its SSD boot drive) and wipe most of the data on my google drive - including other backups related to uni work - which I now cant get back.
### Previous
- No point puting any previous work here, its all gone, What I had done is this:
    - Finish level design in ue5
    - Added and tested interactable interfact for interactible objects in the scene, such as the scanner door, handle, sample tray etc...
    - Designed some of the UI for the scanner
    - Tested out a render using GVXR to check how data is passed and how the scenegraph works
### Planned
- Recreate everything
    - Recreate scanner model
    - Recreate interactable interface and relevant interaction classes
    - Recreate materials and the scene
    - Recreate C++ interface for gvxr-blueprint for ue5
    - Stress because I've got a month to re-do everything.

### Future backups
- Everything in the future will be backed up onto my webserver on oracle cloud (as I trust their hardware more than mine now), using an sshfs share or samba share over a VPN. 
- Samba is preferable because it works like a normal network file share so I wont even have to download the project to work on it.
