# ISZ-3DS-Save-File-Editing
Save-Edit your Nintendo 3DS saves with this method of save-editing.

# How can I save edit my game?

- You'll need to have the decrypted save file(s).

- A hacked 3DS with Luma3ds & Checkpoint or JKSM

- Data0, Data1, Data2, Data3

- Data0 is the Player Information, Health, Time, Inventory, Items, Item Amount, Etc.

- Data3 is the World Spawn Information.

- Data1 & Data2 are blacklisted Users + User ID's (Each of these carry 50 users + their ID's).

# Line 0x00000010

- Nothing here to edit. (You'll Corrupt your data).

# Line 0x00000020 

- 00 - 03 = Health (Value of 0F27 will be 9999%). *64 will be 100%*
- 04 - 07 = Hunger (Value of 0F27 will be 9999%). *64 will be 100%*
- 08 - 0B = Thirst (Value of 0F27 will be 9999%). *64 will be 100%*

# Line 0x00000030

- 00 - 03 = Battery (Value of 0F27 will be 9999%). *64 will be 100%*

# Line 0x00000040

- 00 - 03 = Amount of Days Passed (Value of 0F27 will be 9999 Days Passed). *64 will be 100 Days*
- 04 - 07 = KM Walked/Drove (Value of 0F27 will be 9999.0KM Walked/Drove). *64 will be 100.0KM*
- 08 - 0B = Confirmation for KM Walked/Drove (Value of 0F27 will be 9999.0KM Walked/Drove). *64 will be 100.0KM*
- 0C - 0F = Amount of Zombies Killed (Max = 25)

# Line 0x00000050

- 00 - 03 = Amount of Players Killed (Max = 99)
- 04 - 07 = Amount of Vehicles Driven (Max = 99)
- 08 - 0B = Amount of Food/Water Consumed (Max = 99)
- 0C - 0F = Amount of Healing Items Used (Max = 25)

# Download?

- Yeah sure, why the hell not? 😉

- Download Here: [SaveFiles](https://github.com/Cracko298/ISZ-3DS-Save-File-Editing/files/7966812/Data1.zip)

![image](https://user-images.githubusercontent.com/78656905/151711924-8e7bc222-6653-4c08-a491-f9b1c88baf05.png)

![image](https://user-images.githubusercontent.com/78656905/151711937-52de977e-823b-436e-b31f-6b6c1a885459.png)
