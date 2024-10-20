```
/ (Root Directory)
|
├── bin       ─── Contains essential user commands and utilities (e.g., `ls`, `cp`, `mv`)
|                 that are commonly used for basic operations.
|
├── boot      ─── Holds the files necessary for the system boot process, including the
│                 Linux kernel and boot loader configuration.
|
├── dev       ─── Represents device files for hardware components, allowing software to
│                 interact with the system’s hardware.
|
├── etc       ─── Contains configuration files for the system and various services, allowing
│                 customization and management of system settings.
├── home
│   └── user  ─── Directory for user-specific files and personal data, where each user has
│                 their own subdirectory (e.g., /home/rishabh).
|
├── lib       ─── Houses shared libraries that provide essential code and functions used by
│                 various applications and system tools.
|
├── media     ─── Provides mount points for removable media devices, such as USB drives and CDs,
│                 allowing access to external storage.
|
├── mnt       ─── Temporary mount points for additional storage devices, typically used for manually
│                 mounting filesystems.
|
├── opt       ─── Contains optional software packages and add-ons that are not part of the default
│                 installation but can be installed by the user.
|
├── proc      ─── Features virtual files that offer real-time information about system processes and
│                 hardware status, acting as an interface to the kernel.
|
├── root      ─── The home directory for the root user (administrator), containing personal files and
│                 configurations specific to the root account.
|
├── sbin      ─── Contains system binaries for administrative tasks, typically used by the root user for
│                 system management and maintenance.
|
├── tmp       ─── Directory for temporary files that are created by applications and deleted upon system
│                 reboot, ensuring minimal clutter.
├── usr
│   ├── bin   ─── Houses user applications and utilities, providing additional commands beyond those in `/bin`.
|   |
│   ├── sbin  ─── Contains system binaries for administrative tasks that are not necessary for normal users
│   │             but are vital for system operation.
|   |
│   └── lib   ─── Holds additional libraries used by programs in `/usr/bin` and `/usr/sbin`, supporting more
│                 complex software functions.
└── var
    ├── log   ─── Directory for log files that record system events and activities, useful for
    │             troubleshooting and monitoring.
    |
    ├── mail  ─── Contains user mail spool files where incoming emails for users are stored.
    |
    └── spool ─── Queue for various tasks like print jobs and email messages that are temporarily
                  held until they are processed.
```
