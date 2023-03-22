-   [ ] Bot Joined A Server: Bot will check if it was in this server previously to restore settings.
    -   [ ] If it was in this server previously: Bot will throughly check each settings and restore them. If there is an update it will be automatically patched. It will send a message to logs channel. All the setups are listed in next section.
    -   [ ] If this is a new server: Bot will setup everything and add them to database
-   [ ] Initial Setups for the server:

    -   [ ] Creates Dashboard/Modmin channels: These channels are for the admins and moderators to modify the settings of the bot for their server.

        -   [x] Logs: Used for sendind necessary log messages for the moderators and admins.

        -   [ ] Join-Leave: Settings for member joining, leaving and inviting events

            -   [x] Edit/Build messages to send when a event triggers
            -   [ ] Set channels to send those messages
            -   [ ] Extra addons or settings

                -   [ ] Create a private channel for the user. No need to take extra steps to create a support channel for the user.
                -   [ ] Set a role to be given to the user when they join the server.

### Error Handling

-   [ ] Sends you error message with help message if you did something wrong.

-   [x] Submit a error report which will be emailed to developer (not from your email).
        ![submit_error_Demo](https://user-images.githubusercontent.com/72933395/226837034-8bdb805e-5514-4cc2-8759-4b795b19aa05.gif)
