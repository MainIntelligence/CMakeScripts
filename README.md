# CMakeScripts
linux scripts to automate common cmake tasks like installing, running, testing, and even generating CMake scripts through a project.

# Install
1. Download the repo

2. You can use the MakeInstall and XPermissDir scripts in the Scripts directory, or do the process there yourself,
  if you want to use these, ensure you can execute with the command: "chmod u+x path" (give execute permission to file at path)

<hr>
3. Go to the repo directory with the top level CMakeLists.txt. Run the following sequence of commands:

sudo Scripts/MakeInstall

sudo chmod u+x /usr/local/bin/XPermissDir

sudo XPermissDir Scripts

<hr>

These will:

(1) build and install the scripts from this repo to your /usr/local/bin directory (allowing them to be run easily)

(2) Allow XPermissDir in the install directory to be ran.

(3) Run XPermissDir with Scripts as its argument, which gives execution permission to all of the installed scripts brought in from the Scripts directory.
