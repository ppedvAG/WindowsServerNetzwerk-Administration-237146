# cmdlet for Storage Replica

Testen ob die Umgebung die Anforderung für Storage Replica unterstützt.
```powershell
Test-SRTopology -SourceComputerName Server2 -SourceVolumeName F: -SourceLogVolumeName G: -DestinationComputerName Server3 -DestinationVolumeName F: -DestinationLogVolumeName G: -ResultPath C:\Temp\ -DurationInMinutes 2
```

```powershell
New-SRPartnership -SourceComputerName Server2 -SourceRGName rg02 -SourceVolumeName F: -SourceLogVolumeName G: -DestinationComputerName Server3 -DestinationRGName rg03 -DestinationVolumeName F: -DestinationLogVolumeName G: 
```