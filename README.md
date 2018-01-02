## General

This setup is intended to be a bootstrap for mobile development with technologies:
- [**React Native**](https://facebook.github.io/react-native/) as UI rendering technology (based on Javascript)
- **C++** (aka CPP) executed client side for heavy calculation (exp.: computer vision)
- [**djinni**](https://github.com/dropbox/djinni) acting as a bridge between the

## Prerequisites

### General Prerequisites

**Install dependencies**

```bash
$ cd <this-git-repo>
$ git submodule add https://github.com/dropbox/djinni.git deps/djinni
$ npm install
```

**Compile C++ code / Generate Java and Objective C Connectors**
```bash
$ cd <this-git-repo>
$ chmod +x ./run_djinni.sh
$ sh ./run_djinni.sh
```

## Run iOS (Development)

*Not available yet*.

### Prerequisites iOS

*Not available yet*.

### Run iOS

## Run Android (Development)

### Prerequisites Android

**Install required dependencies**
In *Android Studio* click **Tools > Android > SDK Manager**.

Ensure the following components are installed:
- **LLDB**
- **CMake**
- **NDK**

### Run Android

In *Android Studio* click **Run > Run 'App'**
