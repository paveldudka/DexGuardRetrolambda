# DexGuardRetrolambda
DexGuard doesn't play well with retrolambda

# Set up
1. Downdload and install JDK 1.8

2. Set environment variables:

    JAVA8_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_45.jdk/Contents/Home
    
    JAVA7_HOME=/Library/Java/JavaVirtualMachines/jdk1.7.0_75.jdk/Contents/Home
  
3. put dexguard distribution into `libraries/dexguard6.1.19`

4. execute assembleDebug (dexguard is disabled) - make sure it builds correctly

5. execute assembleRelease (dexguard is enabled for release builds) - build fails

