TODO
============
- ConsoleWindow
    - highlight build error.
        - files and lines
    x add "Build", "Run", "Test", "Clear" in toolbar.
    x Monitor checkbox.
    x Add Monitor flag (watch flag) and a monitor button
    x show project title.
    x print task command.
    x Support multiple console window
    - Option to print task environment or other information
      (May use cocoa delegate)

    - Snap & Resize window to right.
        - Add an option to layout windows with Editor.
    - One-line command to test
    - %GO% template variable for replacing go path from launch path.

- Go Get Package Window
    - Add project to the list.
    - Import from a list.
    - Should close "Go get window" automatically if success.
    - Keep the console window for error

- Project Organizer
    - left navigator panel (to list projects)
        - with status icon
    - right content panel for console.

- Documentation Window
    - Quick Search
    - left navigator panel (search package name)
        - package index generator.
        - interface index generator.
        - type index generator.
    - right content panel
        - web view to browse content.

- Notification
    - integrate with Growl.app.
        - Add preference item.
    - integrate with Notification Center.
        - Add preference item.
    - Option to enable success message.
    - Option to enable failure message.
    - Option to setup success sound.
    - Option to setup failure sound.
- Menu
    x Implement "Run" command.
    x Implement "Test" command.
    x Implement "Watch and Run" command.
    x implement "go get" dialog for fetching packages (output to console window)
    x "go get" and create go project settings.

    - Update Project state icon for building and running.

    - Open project directory in termianl (for iTerms.app or Terminal.app)

- Tray Icon
    - Build state icon animation.

- Preferences:
    - GOROOT, GOPATH validation.
    - Integrate Toolbar with switching view
        - doc server configuration
            - custom hostname and port.
        - global environment path editor.
        - cgo flags.
        - auto-update preferences panel.

    - Build Trigger scripts

- AddProject:
    x project setting editing
    - project directory validation
    - custom environment variables for projects.
    x environment path editor.
    - Browserable directory path for creating/editing project.

x Software update service
    x Use Sparkle: https://github.com/andymatuschak/Sparkle/wiki
    x Provide appcast.xml
    - https://github.com/andymatuschak/Sparkle/wiki/customization
    - https://github.com/andymatuschak/Sparkle/wiki/make-preferences-ui
