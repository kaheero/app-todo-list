# APP TODO LIST

Application for recording daily activities

## Technologies
- NodeJS
- Electron

## Building the application with electron

For more information consult [build app electron](https://www.electronjs.org/docs/latest/tutorial/quick-start#package-and-distribute-your-application).

### Dependencies
- make

### Build

```shell
npm run make
```

---

## Create Desktop Shortcut for linux

The app-todo-list.desktop file should be created inside **~/.local/share/applications** by entering the following text command

```shell
[Desktop Entry]
Name=APP Todo List
Exec={ROOT_FOLDER_PROJECT}/out/app-todo-list-linux-x64/app-todo-list
Icon={ROOT_FOLDER_PROJECT}/out/app-todo-list-linux-x64/resources/app/assets/img/icon.png
Terminal=false
Type=Application
StartupNotify=true
Encoding=UTF-8
```