# Reading XC3 ARD/ARH

xbtool.exe -g xb3 -t ExtractArchive -a bf3.arh bf3.ard -o unpack_xbtool

# Replacing file in XC3 ARD/ARH (DLC 2 example)
File replacement command line: xbtool.exe -g xb3 -t ReplaceArchive -a bf3_dlc02.arh bf3_dlc02.ard -i replacements\bdat\sys.bdat -o /bdat/sys.bdat