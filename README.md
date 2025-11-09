# Server-Management-UI
Manage channels, permissions, and scheduling effortlessly. Create and organize text, voice channels, and categories, with the ability to set role-specific access. Easily adjust permissions with a visual editor, allowing for quick management of roles and channel settings. Automate channel openings and closures, schedule actions, and add reasons 
> 💡 **Built for the Zygnal Ecosystem — to download and use this extension, you must be part of the Zygnal Ecosystem.**  
> This extension (cog) is part of the **Zygnal Ecosystem** and is only available through its supported platforms.  
> You can use it with:  
> - The **[Discord Bot Framework](https://github.com/TheHolyOneZ/discord-bot-framework)** — ideal for developers who want full control and flexibility *(includes an integrated extension marketplace)*, or  
> - The **[ZygnalBot](https://zygnalbot.de)** — a prebuilt, plug-and-play Discord bot *(also includes an integrated extension marketplace)*.  
>
> Browse and install extensions at [zygnalbot.com/extension](https://zygnalbot.com/extension).  
> For help or community discussions, join us on Discord: [discord.gg/sgZnXca5ts](https://discord.gg/sgZnXca5ts)
# Server Management UI Extension

## Features

### Channel Management
- Create text channels, voice channels, and categories
- Manage channel permissions with an easy-to-use UI
- Create role-specific channels that are only visible to certain roles
- Organize channels into categories

### Permission Management
- Visual permission editor for channels
- Toggle permissions with buttons (view, send, manage, etc.)
- Easily manage permissions for specific roles
- Supports inheritance (allow, deny, neutral)

### Scheduling System
- Schedule channels to open or close at specific times
- Set date and time for automated actions
- Add reasons for scheduled actions
- View all scheduled actions in a list
- Cancel scheduled actions

### Automated Channels
- Create channels specific to certain roles
- Automatically set up permissions
- Customize channel names with role variables
- Add channel topics and descriptions
- Place channels in specific categories

### Maintenance Mode
- Temporarily restrict access to non-essential channels
- Select which channels remain accessible during maintenance
- Backup and restore channel permissions
- Send announcements when maintenance begins and ends
- Confirmation dialogs for important actions

## Commands
- `!server create` - Create new channels
- `!server permissions` - Manage channel permissions
- `!server schedule` - Schedule channel opening/closing
- `!server schedules` - View all scheduled actions
- `!server cancel` - Cancel a scheduled action
- `!server automated` - Create role-specific channels
- `!server maintenance` - Toggle maintenance mode
