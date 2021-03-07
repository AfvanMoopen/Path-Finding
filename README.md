# PathFindingProject



    ### Linux and Mac
    
    ```bash
    cd PathFindingProject
    cd Build
    cd Release
    cmake ../../ -DCMAKE_BUILD_TYPE="Release"
    make
    make install
    ```

    Debug :
    ```bash
    cd PathFindingProject
    cd Build
    cd Debug
    cmake ../../ -DCMAKE_BUILD_TYPE="Debug"
    make
    make install
    ```

    ```bash
    cd ../../Bin/{Debug|Release}/
    ./PathPlanning ../../Examples/example.xml
    ```
    ### Windows
    Release :
    ```cmd
    cd PathFindingProject
    cd Build
    cd Release
    set PATH
    cmake ../../ -DCMAKE_BUILD_TYPE="Release" -G "MinGW Makefiles"
    mingw32-make
    mingw32-make install
    ```

    Debug :

    ```cmd
    cd PathFindingProject
    cd Build
    cd Debug
    set PATH
    cmake ../../ -DCMAKE_BUILD_TYPE="Debug" -G "MinGW Makefiles"
    mingw32-make
    mingw32-make install
    ```

    :

    ```cmd
    cd ../../Bin/{Debug|Release}/
    PathFinding.exe ../../Examples/example.xml
    ```
