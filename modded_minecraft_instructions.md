# Connect to the most legit modded minecraft server in the lands

## Getting set up

### Download forge  
[Click here](https://adfoc.us/serve/sitelinks/?id=271228&url=https://maven.minecraftforge.net/net/minecraftforge/forge/1.12.2-14.23.5.2859/forge-1.12.2-14.23.5.2859-installer.jar). This will download the forge java executable. The link corresponds to the specific version of forge the server is running. 

### Check java installation
Check to see if you have java installed. Open up powershell or your terminal of choice. 
- windows-key + r
- type `powershell`
- hit enter

```
java -version
```

If you have no java installed, then proceed to the next section. If you have a java version greater than 8, than head to the **new java** section. If you have java 8 by default, proceed but skip the java installation. 

### Install java  
Go to [java website](https://www.java.com/download/ie_manual.jsp) and download java. Follow steps for default installation. 

### Install forge client  
Navigate to your downloads. If java is installed, you should be able to double click the file and it will open up the forge installer. The 'Install client' radio button should be selected by default. Hit ok. It will install and you can close out of the program after.

If double clicking the forge jar does not open up the installer, try running it manually from the command line. 
Open up powershell, or your terminal of choice. 

- windows-key + r
- type `powershell`
- enter

```powershell
cd .\Downloads\
java -jar .\forge-1.12.2-14.23.5.2859-installer.jar
```

### Modify minecraft config file
- windows-key + r
- type `%appdata%`
- hit enter

Click on `.minecraft` and then `config`.  
Open up `forge.cfg` with notepad or any text editor.  
Set `allowEmissiveItems` to `false`. (line 17)  

Reason for this change can be found on the [mod page](https://www.curseforge.com/minecraft/mc-mods/vics-modern-warfare-mod).

### Install the mods 

**Open up the minecraft launcher!**

Make sure the forge installation is selected (located to the left hand side of the play button). If you have mutliple installations of the forge client on your system, you will have to select the right one. We use `1.12.2-forge-14.23.5.2859`. 

Select multiplayer and choose direct connection. 

Enter in my IP address and you should be able to connect!

Done!


<br />


## New Java 

If you have a new version of java you suck and it makes this process harder. You need to manually specify what version of java you are running for this to work correctly.

download and install java 8  
Go to [java website](https://www.java.com/download/ie_manual.jsp) and download java. Follow steps for default installation. 

Proceed with the rest of the steps, the only step you do differently is 

To run a specific version of java 
```
& 'C:\Program Files\Java\jre-1.8\bin\java.exe' -jar .\forge-1.12.2-14.23.5.2859-installer.jar
```

