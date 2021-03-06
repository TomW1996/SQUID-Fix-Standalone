SQUID-Fix-Standalone
====================

Standalone executable for chemists without an internet connection!

SQUID-Fix is a tool designed for chemistry students. It will correct your SQUID data
for long moment and then use that to calculate Chi and ChiT. After this, it will 
return a file containing:
- Temperature
- Uncorrected Long Moment
- Long Moment
- Uncorrected Chi
- Chi
- Uncorrected ChiT
- ChiT

1) Copy your data files into the 'Data_Files' folder.<br />
2) Open 'config.txt' and fill in the data fields.<br />
3) If you didn't use Eicosane, set the related fields to '0' with the file path field as 'Data_Files/'.<br />
4) If you don't wish to use the Pascal correction, set that field to '0'.<br />
5) All other fields are required - you may use our gel cap and Eicosane data by using 'Data_Files/gelcapData.txt' and 'Data_Files/eicosane.txt' if you wish.<br />
6) Run 'SQUID-Fix.exe'.<br />
7) Collect your corrected data file from the 'Data_Files' folder.<br />
