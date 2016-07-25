# nullinux
####About
nullinux is an internal penetration testing tool for Linux that can be used to enumerate OS information, shares, directories, and users through SMB null sessions. Unlike many of the enumeration tools out there already, nullinux can be executed on multiple machines at once.

This program assumes Python 2.7 and the Samba package are installed on the machine.

###Usage
./nullinux.py -sT -v --enumusers 10.0.0.1-10<br>
./nullinux.py -sN -U Administrator -P password --all 10.0.0.10<br>
./nullinux.py 10.0.0.1-255<br><br>
See the examples section for commands, output, and more.


####Download
nullinux.py:<br>
git clone https://github.com/m8r0wn/nullinux<br><br>
