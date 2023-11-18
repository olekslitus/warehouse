# Crane - Lift your C++ toolchain

Crane does not replace CMake, it simply makes it easier to start projects in C++.
For high granularity and control you can transition to full CMake later on.

## Usage
### Create
```shell
# Create new directory and initialize a C++ project in it
$ crane new project
```

```shell
# Initialize C++ project in the current directory
$ crane init .
```

### Build
```shell
$ crane build
```

### Add
```shell
$ crane add librdkafka
```

### List
```shell
# List current dependecies
$ crange list
```

### Test

### Lint

### Migrate
```shell
# Migrate the project in current directory to use crane
crane migrate .
```


## Other
- https://cliutils.gitlab.io/modern-cmake/chapters/intro/running.html
- https://julienjorge.medium.com/an-overview-of-build-systems-mostly-for-c-projects-ac9931494444
- https://stackoverflow.com/questions/6914524/how-to-generate-cmakelists-txt
- https://conan.io/
- https://vcpkg.io/en/
- https://caiorss.github.io/C-Cpp-Notes/package-managers.html