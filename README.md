# Forensic Toolkit


Located below is a toolkit with several useful forensic tools that could be used on a daily basis. 


## Table of Contents


  * [Network Capture and Analysis](#NetworkCapture)
    * [WinPcap](#WinPcap)
    * [Tcpdump](#tcpdump)
    * [Wireshark](#Wireshark)
  * [Memory Capture](memCapture)
    * [LiME](#lime)
    * [Netcat](#netcat)
  * [Host Acquisition](#HostAcquisition)
    * [FTK Imager](#FTKI)
  * [Analyzing Storage](#storageAnalyzation)
    * [Autopsy](#Autopsy)
    * [FTK](#FTK)
  * [Analyzing Memory](#storageAnalyzation)
    * [Volatility](#Volatility)
    * [Rekall](#rekall)



 ## <a name="NetworkCapture"></a>Network Capture and Analysis
  
  
 ### <a name="WinPcap"></a>WinPCap
 
 
  WinPcap is a networking capture tool for Windows operating systems. it allows you to capture network data to be further analyzed using tools such as Wireshark. Winpcap has ceased development, so another tool may be better used. Wireshark is fully capable of capturing packets on a Windows OS.
  
  
  [WinPcap Download](https://www.winpcap.org/ "WinPcap Download")
  
  
  ### <a name="tcpdump"></a>Tcpdump
  
  
  
  Tcpdump is a command-line tool designed for packet capture. It is a linux tool and allows root users to monitor network traffic. 


`$ tcpdump -h` is a way to see all the options for using tcpdump. the default setting of Tcpdump is to capture the traffic on all network devices, and that is used with '$ tcpdum -D' to output a capture file, you would use a similar command to: `$ sudo tcpdump -i ens33 -vvv -w capture` replaceing ens33 with the network device you would like to capture from. After you have done this, you cant ake the file and analyze it in Wireshark.
  
  
  [Tcpdump Download](https://www.tcpdump.org/#latest-releases "Tcpdump Download")
  
  
  ### <a name="Wireshark"></a>Wireshark
  
  
  
  Wireshark is a network sniffing and analyzing tool that allows users to visually see and filter sets of network data. It's fairly straight forward to use, but if assistance is needed, check out this [link](https://www.howtogeek.com/104278/how-to-use-wireshark-to-capture-filter-and-inspect-packets/).
  
  
  [Wireshark Download](https://www.wireshark.org/ "Wireshark Download")
  
  
 ## <a name="memCapture"></a>Memory Capture
 
 
 ### <a name="lime"></a>LiME
 
 
 Linux Memory Extractor is a Loadable Kernel Module (LKM) which allows for volatile memory acquisition from Linux and Linux-based devices, such as Android. This makes LiME unique as it is the first tool that allows for full memory captures on Android devices. It also minimises its interaction between user and kernel space processes during acquisition, which allows it to produce memory captures that are more forensically sound than those of other tools designed for Linux memory acquisition.
 
 
 [LiME Info](https://github.com/504ensicsLabs/LiME "LiME Info")
 
 
  ### <a name="netcat"></a>Netcat
  
  
  
  [Netcat Download](http://netcat.sourceforge.net/download.php "Netcat Download")


## <a name="HostAcquisition"></a>Host Acquisition 


### <a name="FTKI"></a>FTK Imager


FTK Imager can be used for many imaging tasks including capturing the memory of a system, and the hard drive of a system. 
To capture memory, select File then Capture Memory, and select where you want the file to be stored. 


 [FTK Imager Download](https://accessdata.com/product-download/ftk-imager-version-4.2.0 "FTK Imager Download")


## <a name="storageAnalyzation"></a>Analyzing Storage 


### <a name="FTK"></a>FTK




 [FTK Download](https://accessdata.com/product-download "FTK Download")
 
 
 ### <a name="Autopsy"></a>Autopsy
 
 
 [Autopsy Download](https://www.sleuthkit.org/autopsy/ "Autopsy Download")
 
 
 ### <a name="winprefetch"></a>WinPrefetchView
 
 
 [WinPRefetchView 64bit Download](https://www.nirsoft.net/utils/winprefetchview-x64.zip "WinPrefetchViewDownload")
 
 
## <a name="memAnalyzation"></a>Analyzing Memory 


 ### <a name="volatility"></a>Volatility
 
 
 Volatility is a memory analysis tool. 
 
 
 [Volatility Download](https://www.volatilityfoundation.org/releases "Volatility Download")
 
 
  ### <a name="rekall"></a> Rekall


Rekall is a memory analysistool 


 [Rekall Download](http://www.rekall-forensic.com/releases "Rekall Download")
 

