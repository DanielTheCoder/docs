all: WellKnownServiceTypeEntry_Server.exe WellKnownServiceTypeEntry_Client.exe

WellKnownServiceTypeEntry_Server.exe: WellKnownServiceTypeEntry_Server.cpp WellKnownServiceTypeEntry_Share.dll
	cl /clr:pure WellKnownServiceTypeEntry_Server.cpp

WellKnownServiceTypeEntry_Client.exe: WellKnownServiceTypeEntry_Client.cpp WellKnownServiceTypeEntry_Share.dll
	cl /clr:pure WellKnownServiceTypeEntry_Client.cpp

WellKnownServiceTypeEntry_Share.dll: WellKnownServiceTypeEntry_Share.cpp
	cl /clr:pure /LD WellKnownServiceTypeEntry_Share.cpp
