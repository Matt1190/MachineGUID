$RegPath= 'HKLM:\SOFTWARE\Microsoft\Cryptography\'
$TestPath= '\\CANTON-IT\Users\VictoryAdmin\Desktop\DuoCSV\TestGUID.csv'

Get-ItemProperty -path $RegPath -Name MachineGUID |
Select-Object -Property MachineGUID | 
    Add-Content -path $TestPath 
