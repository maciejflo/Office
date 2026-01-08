Visio 2019:
$exe = "C:\Program Files\Common Files\Microsoft Shared\ClickToRun\OfficeClickToRun.exe"
$args = 'scenario=install scenariosubtype=ARP sourcetype=None productstoremove=VisioStd2019Volume.16_en-us_x-none culture=en-us version.16=16.0'
Start-Process -FilePath $exe -ArgumentList $args -Verb RunAs -Wait

Project 2016:
"C:\Program Files\Common Files\Microsoft Shared\ClickToRun\OfficeClickToRun.exe" scenario=install scenariosubtype=ARP sourcetype=None productstoremove=ProjectProXVolume.16_en-us_x-none culture=en-us version.16=16.0

Visio Plan 2:
"C:\Program Files\Common Files\Microsoft Shared\ClickToRun\OfficeClickToRun.exe" scenario=install scenariosubtype=ARP sourcetype=None productstoremove=VisioProRetail.16_en-us_x-none culture=en-us version.16=16.0
