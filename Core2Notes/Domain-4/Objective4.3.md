# Objective 4.3 - Workstation Backup and Recovery Methods

# Backup

### Full Backup

**Definition:** A backup that copies all selected data every time it runs.
**Example:** Backing up an entire workstation to an external drive every Sunday.

### Incremental Backup

**Definition:** A backup that copies only data changed since the last backup.
**Example:** Backing up files modified since yesterday's backup.

### Differential Backup

**Definition:** A backup that copies all data changed since the last full backup.
**Example:** Backing up all files changed since Sunday's full backup.

### Synthetic Full Backup

**Definition:** A full backup created by combining a previous full backup with incremental backups.
**Example:** Backup software automatically creating a new full backup without re-copying all files.

---

# Recovery

### In-Place/Overwrite Recovery

**Definition:** Restoring data to its original location and replacing existing files.
**Example:** Restoring a deleted document back to the user's Documents folder.

### Alternative Location Recovery

**Definition:** Restoring data to a different location than its original destination.
**Example:** Recovering files from a failed PC to a network share.

---

# Backup Testing

### Frequency

**Definition:** How often backups are tested to verify successful recovery.
**Example:** Performing a backup restore test once per month.

---

# Backup Rotation Schemes

### Onsite Backup

**Definition:** Backups stored at the same physical location as the original data.
**Example:** Saving backups to a local NAS in the server room.

### Offsite Backup

**Definition:** Backups stored at a different physical location from the original data.
**Example:** Storing backups in a cloud storage service.

### Grandfather-Father-Son (GFS)

**Definition:** A backup rotation method using daily, weekly, and monthly backups.
**Example:** Daily backups kept for one week, weekly backups for one month, and monthly backups for one year.

### 3-2-1 Backup Rule

**Definition:** A backup strategy that keeps three copies of data on two different media types with one copy stored offsite.
**Example:** Original files on a PC, a backup on an external drive, and another backup in cloud storage.