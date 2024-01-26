# cmdlet for Storage Replica

Testen ob die Umgebung die Anforderung für Storage Replica unterstützt.
```powershell
Test-SRTopology -SourceComputerName Server2 -SourceVolumeName F: -SourceLogVolumeName G: -DestinationComputerName Server3 -DestinationVolumeName F: -DestinationLogVolumeName G: -ResultPath C:\Temp\ -DurationInMinutes 2
```