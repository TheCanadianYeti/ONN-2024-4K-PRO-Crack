# ONN-2024-4K-PRO-Crack

Start of a Crack for the Jarvis Bootloader on the 2024 ONN 4K pro android tv box

Boot loader information i have collected so far:
(bootloader) hw-revision: 0
(bootloader) battery-voltage: 4
(bootloader) is-userspace: no
(bootloader) is_logical:data: no
(bootloader) is_logical:misc: no
(bootloader) is_logical:super: no
(bootloader) is_logical:boot_a: no
(bootloader) is_logical:boot_b: no
(bootloader) is_logical:system_a: no
(bootloader) is_logical:system_b: no
(bootloader) is_logical:vendor_a: no
(bootloader) is_logical:vendor_b: no
(bootloader) is_logical:product_a: no
(bootloader) is_logical:product_b: no
(bootloader) is_logical:odm_a: no
(bootloader) is_logical:odm_b: no
(bootloader) slot-count: 2
(bootloader) downloadsize: 0x08000000
(bootloader) serialno: ############ - purposely not showing the serial number here
(bootloader) product: jarvis
(bootloader) unlocked: no
(bootloader) has-slot:data: no
(bootloader) has-slot:metadata: no
(bootloader) has-slot:misc: no
(bootloader) has-slot:super: no
(bootloader) has-slot:boot: yes
(bootloader) has-slot:system: yes
(bootloader) has-slot:vendor: yes
(bootloader) has-slot:product: yes
(bootloader) has-slot:odm: yes
(bootloader) current-slot: b
(bootloader) secure: yes
(bootloader) super-partition-name: super
(bootloader) version-baseband: N/A
(bootloader) version-bootloader: 01.01.250529.170449
(bootloader) partition-size:super: 0x0000000180000000
(bootloader) partition-size:boot_a: 0x0000000006000000
(bootloader) partition-size:boot_b: 0x0000000006000000
(bootloader) partition-size:misc: 0x0000000000200000
(bootloader) partition-size:userdata: 0x0000000575a00000

you need to download the android platform tools from https://developer.android.com/tools/releases/platform-tools
i initally got the device connected to my computer and i used zadig (https://zadig.akeo.ie/) (ran as admin) in order to get the drivers working on my computer

upon entering the tools folder in the terminal i ran: ".\fastboot devices", you should get a serial number at this point.

at the current moment running: " .\fastboot flashing unlock", 
returns an error: 
FAILED (remote: 'locked device')
fastboot: error: Command failed

i have not gotten past this point yet, i need to figure out how to unlock it. 
please feel free to contribute to this project if you have fouund any further information related to cracking the jarvis bootloader