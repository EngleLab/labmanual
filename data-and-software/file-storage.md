# 🗃 File Storage

We use Microsoft SharePoint to store and sync most of our files. However, we also store files on Dropbox, a Georgia Tech Z: drive server, and backup hard drives in the lab.

### SharePoint

SharePoint functions just like Google Drive (e.g., Google Docs, Sheets, etc.) but more Microsoft documents (e.g., Word, Excel, ect.).&#x20;

Although SharePoint is synced locally on the control room computers (through OneDrive), it is highly advised to access files on SharePoint in the browser when on the control room computers. This ensures that you are accessing the most recent version of documents and to avoid any syncing issues between computers.

We have created SharePoint "Pages" to easily access frequently used documents for our ongoing projects in the lab.&#x20;

Our main SharePoint page is for the Control Room and can be accessed [here](https://gtvault.sharepoint.com/sites/cos/psychology/engle-lab/SitePages/Control-Room.aspx). There is a bookmark to the SharePoint page on the control room computer's Edge Browser so you should always have easy access to it.

For now, there are three main folders on our lab's SharePoint:

* **Control Room**\
  Files related to operations in the control room are stored here. RA schedules, participant schedules, email templates, running room log notebook, etc.
* **Data Collection**\
  Files for every data collection study are stored here. This serves as a backup and a repository to access data files.
* **Data Analysis**\
  Files for data analysis projects (intended for publication or just exploration of our data) are stored here.&#x20;

### Z: Drive

The running room computers have restricted network access so we cannot upload or sync files through services like SharePoint. Therefore, the Z: drive acts as a central server to move files to and from the running room computers and our other lab computers.&#x20;

We use the Z: drive to:

1. **Store the Subject Database**\
   This is where we store sensitive and identifiable data on our subjects that have participated in all the studies in our lab going back many years. This is a very important document and needs to be updated with every participant that comes in.
2. **Copy subject data files** \
   Data files from an ongoing data collection study need to be copied over to the Z: drive and eventually onto SharePoint from another computer in the lab. Every study will have an R script called copy\_to\_zdrive.R that will automatically copy over all data files for that study to the Z: drive. RAs can be trained on how to do this process. Graduate students are responsible for writing the R script.
3. **Add and update task files**\
   The Z: drive is a convenient way to add and update E-Prime run files for a study onto each running room computer. It is advised to only add the E-run files (on the Z: drive and locally on the running room computers) to avoid multiple copies and versions of E-Studio files for the same task. If you want to test out and edit your E-Studio scripts on the running room computers I would advise to just do this through a USB thumb drive, and then copy the updated E-Studio file to SharePoint immediately.

The Z: drive has limited storage space, and we would have to pay for more, so it is primarily just used for the temporary transfer of files.&#x20;

### Backup Hard Drive

We have a 12 TB backup hard drive in our lab. We use this as a general backup for lab data and files.

When a data collection study is finished, we back up all the raw data files to the hard drive as a backup of what is on SharePoint.

Also, given that eye tracking data files can use up a lot of storage we also use it as a central repository for our eye tracking data.

### Dropbox

We also have some lab files and even study data files stored on Dropbox. This is mainly because we started with Dropbox and have not ported it all over to SharePoint.

Some critical documents we have on Dropbox are:

* Lab website files
* Task download files from our website
* Grant documents
* IRB documents&#x20;
* Data files from older studies in our lab

Dropbox is also locally synced to both contorol room computers
