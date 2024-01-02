# Hardware-Upgrade
Lenovo Thinkpad T430s Revitalization and Upgrade Project
Project Title: Lenovo ThinkPad T430s Revitalization and Upgrade Project

Objective: Upgrade and revitalize an old Lenovo ThinkPad T430s by enhancing its hardware components, resolving BIOS issues, and installing a new operating system for improved performance and functionality.

Project Tasks:

1.  RAM Upgrade:

    -   Upgraded the existing RAM from 4GB to 16GB (2x8GB) using a PC3-12800 DDR3L kit.
2.  BIOS Error Resolution:

    -   Encountered BIOS error message "0271 Real-Time Clock Error."
    -   Attempted to resolve by removing and reseating CMOS; however, the issue persisted.
    -   Bypassed the password lock by shorting two pins on the motherboard.
    -   Successfully removed the password requirement.
3.  CMOS Battery Replacement:

    -   Identified a defective CMOS battery affecting date and time persistence.
    -   Purchased and replaced the defective CMOS battery with an LJCELL CMOS Battery compatible with Lenovo ThinkPad laptops.
4.  SSD Upgrade:

    -   Upgraded the old 128GB SSD to a Crucial MX500 250GB 3D NAND SATA 2.5-inch SSD with a 9.5mm adapter for improved storage and data access speeds.
5.  Operating System Installation:

    -   Created a bootable USB drive with the Centos Linux ISO file using Rufus.
    -   Installed Centos Stream 9 on the upgraded hardware.
6.  Operating System Update:

    -   Executed the following commands to update and upgrade the operating system:

        sqlCopy code

        `sudo dnf update -y
        sudo dnf upgrade -y`

7.  Hardware Clock Issue Resolution:

    -   Fixed the hardware clock issue by switching to root:

        Copy code

        `su root`

    -   Synchronized the hardware clock:

        cssCopy code

        `hwclock --systohc`

Testing and Quality Assurance:

-   Validate the upgraded RAM capacity through system diagnostics.
-   Verify the successful removal of the BIOS password requirement.
-   Confirm the new CMOS battery's effectiveness in maintaining date and time settings.
-   Test the performance improvements with the upgraded SSD.
-   Ensure the successful installation and functionality of the Centos Stream 9 operating system.

Conclusion: This project aims to extend the life and enhance the performance of the Lenovo ThinkPad T430s by addressing hardware limitations, resolving BIOS issues, and installing an updated operating system. The thorough testing and quality assurance processes ensure a reliable and optimized computing experience for the end user.
