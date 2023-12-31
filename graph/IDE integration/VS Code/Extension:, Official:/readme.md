# Official: Meson for Visual Studio Code
Home: https://github.com/mesonbuild/vscode-meson
- https://marketplace.visualstudio.com/items?itemName=mesonbuild.mesonbuild

# Guide:
https://www.collabora.com/news-and-blog/blog/2023/04/18/meson-and-vscode-develop-your-project-modern-ide/

# Features:
## C/C++ Intellisense
quote:
>If Microsoft's Intellisense extension is installed, it will be automatically configured to use the compile_commands.json file generated by Meson in your build directory. This allows VSCode's C and C++ syntax analyzer to find and include the paths and CFLAGS needed.
—https://www.collabora.com/news-and-blog/blog/2023/04/18/meson-and-vscode-develop-your-project-modern-ide/

## Launch task in developer environment
quote:
>Meson provides a developer environment to run executables from your project without installing it. It consists on a set of environment variables that needs to be set in order to properly run the project, such as LD_LIBRARY_PATH, GST_PLUGIN_PATH (GStreamer), etc.
>
>The Meson VSCode extension exports that environment into a file that can be used by VSCode's launch.json file's envFile attribute.
>
>If your project provides a .vscode/launch.json file, F5 will run the program in the debugger, allowing you to inspect a variable's value and step line by line into your code directly in VSCode.
>
>See GStreamer's launch.json file as example: https://gitlab.freedesktop.org/gstreamer/gstreamer/-/blob/main/.vscode/launch.json.
—https://www.collabora.com/news-and-blog/blog/2023/04/18/meson-and-vscode-develop-your-project-modern-ide/
