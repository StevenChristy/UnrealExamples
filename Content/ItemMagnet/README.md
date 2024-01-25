# Item Magnet Actor

Keep this as a seperate actor and attach it to your Pawn using the following logic in begin play:

![Create ItemMagnet Actor and Attach to Pawn](https://github.com/StevenChristy/UnrealExamples/blob/main/Images/CreateItemMagnet.png?raw=true)

There is nothing particular special about BP_Collectable other than BP_ItemMagnet is only picking up items of type BP_Collectable. You could easily customize this to detect items by interface or another item. The collected item does need to be able to generate overlap events though.
