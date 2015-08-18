#Wireshark Change Logs

##Wireshark 1.10.0 Release Notes

###New and Updated Features

The following features are new (or have been significantly updated) since version 1.8:

- Wireshark on 32- and 64-bit Windows supports automatic updates.
- The packet bytes view is faster.
- You can now display a list of resolved host names in "hosts" format within Wireshark.
- The wireless toolbar has been updated.
- Wireshark on Linux does a better job of detecting interface addition and removal.
- It is now possible to compare two fields in a display filter (for example: udp.srcport != udp.dstport). The two fields must be of the same type for this to work.
- The Windows installers ship with WinPcap 4.1.3, which supports Windows 8.
- USB type and product name support has been improved.
- All Bluetooth profiles and protocols are now supported.
- Wireshark now calculates HTTP response times and presents the result in a new field in the HTTP response. Links from the request’s frame to the response’s frame and vice-versa are also added.
- The main welcome screen and status bar now display file sizes using strict SI prefixes instead of old-style binary prefixes.
- Capinfos now prints human-readable statistics with SI suffixes by default.
- It is now possible to open a referenced packet (such as the matched request or response packet) in a new window.
- Tshark can now display only the hex/ascii packet data without requiring that the packet summary and/or packet details are also displayed. If you want the old behavior, use -Px instead of just -x.
- Wireshark can be compiled using GTK+ 3.
- The Wireshark application icon, capture toolbar icons, and other icons have been updated.
- Tshark’s filtering and multi-pass analysis have been reworked for consistency and in order to support dependent frame calculations during reassembly. See the man page descriptions for -2, -R, and -Y.
- Tshark’s -G fields2 and -G fields3 options have been eliminated. The -G fields option now includes the 2 extra fields that -G fields3 previously provided, and the blurb information has been relegated to the last column since in many cases it is blank anyway.
- Wireshark dropped the left-handed settings from the preferences. This is still configurable via the GTK settings (add "gtk-scrolled-window-placement = top-right" in the config file, which might be called /.gtkrc-2.0 or /.config/gtk-3.0/settings.ini).
- Wireshark now ships with two global configuration files: Bluetooth, which contains coloring rules for Bluetooth and Classic, which contains the old-style coloring rules.
- The LOAD() metric in the IO-graph now shows the load in IO units instead of thousands of IO units.


###New Protocol Support

Amateur Radio AX.25, Amateur Radio BPQ, Amateur Radio NET/ROM, America Online (AOL), AR Drone, Automatic Position Reporting System (APRS), AX.25 KISS, AX.25 no Layer 3, Bitcoin Protocol, Bluetooth Attribute Protocol, Bluetooth AVCTP Protocol, Bluetooth AVDTP Protocol, Bluetooth AVRCP Profile, Bluetooth BNEP Protocol, Bluetooth HCI USB Transport, Bluetooth HCRP Profile, Bluetooth HID Profile, Bluetooth MCAP Protocol, Bluetooth SAP Profile, Bluetooth SBC Codec, Bluetooth Security Manager Protocol, Cisco GED-125 Protocol, Clique Reliable Multicast Protocol (CliqueRM), D-Bus, Digital Transmission Content Protection over IP, DVB-S2 Baseband, FlexNet, Forwarding and Control Element Separation Protocol (ForCES), Foundry Discovery Protocol (FDP), Gearman Protocol, GEO-Mobile Radio (1) RACH, HoneyPot Feeds Protocol (HPFEEDS), LTE Positioning Protocol Extensions (LLPe), Media Resource Control Protocol Version 2 (MRCPv2), Media-Independent Handover (MIH), MIDI System Exclusive (SYSEX), Mojito DHT, MPLS-TP Fault-Management, MPLS-TP Lock-Instruct, NASDAQ’s OUCH 4.x, NASDAQ’s SoupBinTCP, OpenVPN Protocol, Pseudo-Wire OAM, RPKI-Router Protocol, SEL Fast Message, Simple Packet Relay Transport (SPRT), Skype, Smart Message Language (SML), SPNEGO Extended Negotiation Security Mechanism (NEGOEX), UHD/USRP, USB Audio, USB Video, v.150.1 State Signaling Event (SSE), VITA 49 Radio Transport, VNTAG, WebRTC Datachannel Protocol (RTCDC), and WiMAX OFDMA PHY SAP

###Updated Protocol Support

Too many protocols have been updated to list here.

###New and Updated Capture File Support

AIX iptrace, CAM Inspector, Catapult DCT2000, Citrix NetScaler, DBS Etherwatch (VMS), Endace ERF, HP-UX nettl, IBM iSeries, Ixia IxVeriWave, NA Sniffer (DOS), Netscreen, Network Instruments Observer, pcap, pcap-ng, Symbian OS btsnoop, TamoSoft CommView, and Tektronix K12xx

##Wireshark 1.10.1 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

ANSI IS-637-A, ASN.1, ASN.1 PER, Bluetooth OBEX, Bluetooth SDB, DCERPC NDR, DCOM ISystemActivator, DCP ETSI, Diameter 3GPP, DIS, DVB-CI, Ethernet, GSM Common, GSM SMS, H.235, IEC104, IEEE 802.15.4, IEEE 802a, IMAP, IP, KDSP, LISP, LLRP, MAC-LTE,, Mobile IPv6, MONGO, MPLS Echo, Netflow, NFS, NFSv4, P1, PDCP-LTE, PN-IO, PN-RT, PPP, Radiotap, RLC,, RLC-LTE,, SCSI, SIP, SMTP, SoulSeek, TCP, TETRA, and VNC

###New and Updated Capture File Support

and Microsoft Network Monitor, pcap-ng.

##Wireshark 1.10.2 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

ASN.1 PER, ASSA R3, Bluetooth HCI ACL, EtherCAT AMS, GTPv2, HTTP, IEEE 802.11, IPFIX, ISDN SUP, LDAP, MQ, NBAP, Novell SSS, PROFINET MRP, Radiotap, ROHC, RTPS, SCSI, SIP, and STP

###New and Updated Capture File Support

and Microsoft Network Monitor, pcap-ng.

##Wireshark 1.10.3 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

3GPP2 A11, Bluetooth SDP, BSSGP, DCERPC, DCERPC NDR, DCERPC NT, DIAMETER, DNS, DVB-S2, Ethernet, EtherNet/IP, H.225, IEEE 802.15.4, IRC, NBAP, NTLMSSP, OpenWire, PTP, RTP, SIP, TCP, WiMax, and XMPP

###New and Updated Capture File Support

and .

##Wireshark 1.10.4 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

ANSI IS-637-A, BSSGP, DNP3, DVB-BAT, DVB-CI, GSM MAP, GSM SMS, IEEE 802.11, iSCSI, NFSv4, NTLMSSP v2, RLC, SEL FM, SIP, and Time

###New and Updated Capture File Support

and Pcap-ng.

##Wireshark 1.10.5 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

GSM BSSMAP, GSM BSSMAP LE, GSM SMS, Homeplug, NAS-EPS, and SGSAP

###New and Updated Capture File Support

There is no updated capture file support in this release.

##Wireshark 1.10.6 Release Notes

###New and Updated Features

IPv4 checksum verfification is now disabled by default.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

AppleTalk, CAPWAP, DMX-CHAN, DSI, DVB-CI, ESS, GTPv1, IEEE 802a, M3UA, Modbus/TCP, NAS-EPS, NFS, OpenSafety, SDP, and SMPP

###New and Updated Capture File Support

libpcap, MPEG, and pcap-ng

##Wireshark 1.10.7 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

ANSI A, DVB-CI, GSM DTAP, GSM MAP, IEEE 802.11, LCSAP, LTE RRC, MAC LTE, Prism, RTP, SDP, SIP, and TCP

###New and Updated Capture File Support

and There are no changes in this release.

##Wireshark 1.10.8 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

CIP, EtherNet/IP, GSM RLC MAC, IEEE 802.11, IPv6, and TCAP

###New and Updated Capture File Support

pcap-ng, and PEEKREMOTE

##Wireshark 1.10.9 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

###New and Updated Capture File Support

##Wireshark 1.10.10 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

6LoWPAN, DVB-CI, IEEE 802.11, MEGACO, MIPv6, Netflow, NTP, OSI, RPKI RTR, RTP, RTSP, SES, SIP, and UCP

###New and Updated Capture File Support

DOS Sniffer, and NetScaler

##Wireshark 1.10.11 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

6LoWPAN, AMQP, GSM MAP, GTPv2, H.223, IEEE 802.11, iSCSI, MIH, Mobile IPv6, PTPoE, TN5250, and UCP

###New and Updated Capture File Support

Catapult DCT2000, HP-UX nettl, pcap-ng, and Sniffer (DOS)

##Wireshark 1.10.12 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

DEC DNA, DECT, FCoIB, Infiniband, IrDA, LCSAP, MIPv6, NAS EPS, RDM, RSVP, and TCP

###New and Updated Capture File Support

##Wireshark 1.10.13 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

ANSI IS-637-A, DHCP, GSM MAP, H.248, IPv6, Juniper Jmirror, and X.509AF

###New and Updated Capture File Support

PacketLogger, and Pcapng

##Wireshark 1.10.14 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

ASN.1 PER, CANopen, GSM RLC/MAC, GSMTAP, ICMP, IEEE 802.11, LPP, MEGACO, PKCS-1, PPP IPv6CP, SRVLOC, SSL, TCP, WCP, X11, and ZigBee ZCL

###New and Updated Capture File Support

and Savvius OmniPeek Visual Networks

##Wireshark 1.12.0 Release Notes

###New and Updated Features

The following features are new or have been significantly updated since version 1.10:

- The Windows installer now uninstalls the previous version of Wireshark silently. You can still run the uninstaller manually beforehand if you wish to run it interactively.
- Expert information is now filterable when the new API is in use.
- The "Number" column shows related packets and protocol conversation spans (Qt only).
- When manipulating packets with editcap using the -C <choplen> and/or -s <snaplen> options, it is now possible to also adjust the original frame length using the -L option.
- You can now pass the -C <choplen> option to editcap multiple times, which allows you to chop bytes from the beginning of a packet as well as at the end of a packet in a single step.
- You can now specify an optional offset to the -C option for editcap, which allows you to start chopping from that offset instead of from the absolute packet beginning or end.
- "malformed" display filter has been renamed to "\_ws.malformed". A handful of other filters have been given the "\_ws." prefix to note they are Wireshark application specific filters and not dissector filters.
- The Kerberos dissector has been replaced with an auto generated one from ASN1 protocol description, changing a lot of filter names.

Additionally the Windows installers have an extra component: a preview of the upcoming user interface for Wireshark 2.0.

The following features are new (or have been significantly updated) since version 1.11.3:

- Transport name resolution is now disabled by default.
- Support has been added for all versions of the DCBx protocol.
- Cleanup of LLDP code, all dissected fields are now navigable.

The following features are new (or have been significantly updated) since version 1.11.2:


- Qt port:

 -  The About dialog has been added
 - The Capture Interfaces dialog has been added.
 - The Decode As dialog has been added. It managed to swallow up the User Specified Decodes dialog as well.
 - The Export PDU dialog has been added.
 - Several SCTP dialogs have been added.
 - The statistics tree (the backend for many Statistics and Telephony menu items) dialog has been added.
 - The I/O Graph dialog has been added.
 - French translation has updated.

The following features are new (or have been significantly updated) since version 1.11.1:

- Mac OS X packaging has been improved.

The following features are new (or have been significantly updated) since version 1.11.0:

- Dissector output may be encoded as UTF-8. This includes TShark output.

- Qt port:

◦ The Follow Stream dialog now supports packet and TCP stream selection.
◦ A Flow Graph (sequence diagram) dialog has been added.
◦ The main window now respects geometry preferences.

###Removed Dissectors

- The ASN1 plugin has been removed as it’s deemed obsolete.
- The GNM dissector has been removed as it was never used.
- The Kerberos hand made dissector has been replaced by one generated from ASN1 code.

###Platform Support

Support for Windows XP has been deprecated. We will make an effort to support it for as long as possible but our ability to do so depends on upstream packages and other factors beyond our control.

U3 packages are no longer supported or provided.

This is the last major release that will support 32-bit versions of Mac OS X.

###New Protocol Support

29West, 802.1AE Secure tag, A21, ACR122, ADB Client-Server, AllJoyn, Apple PKTAP, Aruba Instant AP, ASTERIX, ATN, Bencode, Bluetooth 3DS, Bluetooth HSP, Bluetooth Linux Monitor Transport, Bluetooth Low Energy, Bluetooth Low Energy RF Info, CARP, CFDP, Cisco MetaData, DCE/RPC MDSSVC, DeviceNet, ELF file format, Ethernet Local Management Interface (E-LMI), Ethernet Passive Optical Network (EPON), EXPORTED PDU, FINGER, HDMI, High-Speed LAN Instrument Protocol (HiSLIP), HTTP2, IDRP, IEEE 1722a, ILP, iWARP Direct Data Placement and Remote Direct Memory Access Protocol, Kafka, Kyoto Tycoon, Landis & Gyr Telegyr 8979, LBM, LBMC, LBMPDM, LBMPDM-TCP, LBMR, LBT-RM, LBT-RU, LBT-TCP, Lightweight Mesh (v1.1.1), Link16, Linux netlink, Linux netlink netfilter, Linux netlink sock diag, Linux rtnetlink (route netlink), Logcat, MBIM, Media Agnostic USB (MA USB), MiNT, MP4 / ISOBMFF file format, MQ Telemetry Transport Protocol, MS NLB (Rewrite), Novell PKIS certificate extensions, NXP PN532 HCI, Open Sound Control, OpenFlow, Pathport, PDC, Picture Transfer Protocol Over IP, PKTAP, Private Data Channel, QUIC (Quick UDP Internet Connections), SAE J1939, SEL RTAC (Real Time Automation Controller) EIA-232 Serial-Line Dissection, Sippy RTPproxy, SMB-Direct, SPDY, STANAG 4607, STANAG 5066 DTS, STANAG 5066 SIS, Tinkerforge, Ubertooth, UDT, URL Encoded Form Data, USB Communications and CDC Control, USB Device Firmware Upgrade, VP8, WHOIS, Wi-Fi Display, and ZigBee Green Power profile

###Updated Protocol Support

Too many protocols have been updated to list here.

###New and Updated Capture File Support

Netscaler 2.6, STANAG 4607, and STANAG 5066 Data Transfer Sublayer

###Major API Changes

The libwireshark API has undergone some major changes:

- A more flexible, modular memory manager (wmem) has been added. It was available experimentally in 1.10 but is now mature and has mostly replaced the old emem API (which is deprecated).
- A new API for expert information has been added, replacing the old one.
- The tvbuff API has been cleaned up: tvb_length has been renamed to tvb_captured_length for clarity, and tvb_get_string and tvb_get_stringz have been deprecated in favour of tvb_get_string_enc and tvb_get_stringz_enc.
- dissector_try_heuristic() signature has been changed to return heur_dtbl_entry_t to make it possible to save it and use it in subsequent calls to avoid the overhead of going trough the heuristics list.

##Wireshark 1.12.1 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

6LoWPAN, A21, ACR122, Art-Net, AX.25, BGP, BTLE, CAPWAP, DIAMETER, DICOM, DVB-CI, Ethernet OAM, HIP, HiSLIP, HTTP2, IEEE 802.11, MAUSB, MEGACO, MIPv6, MP2T, Netflow, NTP, openSAFETY, OSI, RDM, RPKI RTR, RTSP, SES, SIP, TLS, and Token Ring MAC

###New and Updated Capture File Support

DOS Sniffer, and NetScaler

##Wireshark 1.12.2 Release Notes

###New and Updated Features

There are no new features in this release.

The Windows installers no longer include previews of Wireshark 2. If you want to try the new user interface, please download a development (1.99) installer.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

6LoWPAN, AMQP, ANSI IS-637-A, Bluetooth HCI, CoAP, DCERPC (all), DCERPC NT, DNS, GSM MAP, GTPv2, H.223, HPSW, HTTP2, IEEE 802.11, IPv6, iSCSI, Kerberos, LBT-RM, LLDP, MIH, Mobile IPv6, MQ, NCP, OpcUa, OpenFlow, PKTAP, PTPoE, SigComp, SMB2, SMPP, SPDY, Stanag 4607, T.125, UCP, USB CCID, and WCCP

###New and Updated Capture File Support

Catapult DCT2000, HP-UX nettl, Ixia IxVeriWave, pcap, pcap-ng, RADCOM, and Sniffer (DOS)

##Wireshark 1.12.3 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

6LoWPAN, ADwin, AllJoyn, Art-Net, Asterix, BGP, Bitcoin, Bluetooth OBEX, Bluetooth SDP, CFM, CIP, DCERPC PN-IO, DCERPC SPOOLSS, DEC DNA, DECT, DHCPv6, DNS, DTN, E-LMI, ENIP, Ethernet, Extreme, FCoIB, Fibre Channel, GED125, GTP, H.248, H.264, HiSLIP, IDRP, IEEE 802.11, IEEE P1722.1, Infiniband, IrDA, iSCSI, ISUP, LBMR, LCSAP, LPP, MAC LTE, MAUSB, MBIM, MIM, MIP, MIPv6, MP2T, MPEG-1, NAS EPS, NAT-PMP, NCP, NXP PN532, OpcUa, OpenFlow, PTP, RDM, RPKI-RTR, RSVP, RTnet, RTSP, SCTP, SMPP, SMTP, SPDY, Spice, TCP, WCCP, Wi-Fi P2P, and WiMAX

###New and Updated Capture File Support

and K12

##Wireshark 1.12.4 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

ACN, ANSI IS-637-A, AppleMIDI, ATN-CPDLC, BGP, BSSGP, CMIP, DHCP, DHCPv6, DIS, DLM3, DMP, DNS, Extreme Networks, ForCES, FTAM, GMHDR, GSM A BSSMAP, GSM A-bis OML, GSM MAP, GSM RLC MAC, GTP, H.248, H.264, HTTP, IEEE 802.11, IPv6, IS-IS, ISMACryp, J1939, Juniper Jmirror, KDP, L2CAP, LDAP, LLDP, MGCP, MIP6, NBNS, NET/ROM, Netflow, Novell PKIS, PANA, PPPoE, RSL, RSYNC, RTMPT, RTP, SCSI OSD, SDP, SMB Pipe, SMPP, SYNCHROPHASOR, TETRA, TiVoConnect, TNEF, USB HID, V.52, VSS-Monitoring, X.509AF, Zebra, and ZigBee

###New and Updated Capture File Support

NetScaler, PacketLogger, and Pcapng

##Wireshark 1.12.5 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

AllJoyn, ASN.1 PER, ATM, CANopen, Diameter, ForCES, GSM RLC/MAC, GSMTAP, ICMP, IEC-60870-5-104, IEEE 802.11, IMF, IP, LBMC, LBMR, LDAP, LPP, MBIM, MEGACO, MP2T, PKCS-1, PPP IPv6CP, RPC, SPNEGO, SRVLOC, SSL, T.38, TCP, USB, WCP, WebSocket, X11, and ZigBee ZCL

###New and Updated Capture File Support

and Android Logcat Savvius OmniPeek Visual Networks

##Wireshark 1.12.6 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

GSM DTAP, iSCSI, P1, PCP, SIP, and WCCP

###New and Updated Capture File Support

There is no new or updated capture file support in this release.

##Wireshark 1.12.7 Release Notes

###New and Updated Features

There are no new features in this release.

###New Protocol Support

There are no new protocols in this release.

###Updated Protocol Support

Aruba ERM, CFM, EPL, GSM A-bis OML, GSM MAP, GSM RLC/MAC, GTPv2, IEEE 802.11, LLDP, LTE RRC, MAC Control, MQ, MySQL, OpcUa, OpenFlow, Radiotap, SCCP, SOCKS, TCP, WaveAgent, WCCP, and ZigBee

###New and Updated Capture File Support

There is no new or updated capture file support in this release.
