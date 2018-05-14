# eclipse-freertos-stm32f4disco
The project is my attempt to start with freertos on stm32f4discovery board using eclipse environment.
Following are the steps for configuration and startup.

Download and install eclipse neon (neon worked well for me);


Download Cross-Toolchain for ARM Cortex Processor prefer downloading zip file and extract it in a setup folder outside your workspace.
https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads


Install the GNU MCU eclipse plugins.
Help -> Install new software -> Add Repository
Name it as GNU MCU Eclipse Plugin
Location : http://gnu-mcu-eclipse.netlify.com/v4-neon-updates/
Install all.


Download build tools(only for windows);
because eclipse use commands like make, rm, mkdir etc.
https://github.com/gnu-mcu-eclipse/windows-build-tools
goto releases and download the latest zip file and extract it in the setup folder.



Download and install OpenOCD
https://github.com/gnu-mcu-eclipse/openocd/releases/tag/gae-0.10.0-20170124
This one worked for me the latest one was causing trouble in loading and debugging.
Download and install in the seetup folder. We may need the executable for the setup.



Download and install stmcube MX software.

Select the board and generate basic code for stm32f4discovery or whatever board you are using.
Generate it as SW4STM32.










