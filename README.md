# canon-selphy-print
Suport for Canon SELPHY CP1200/CP1300 and other compatible printers.


# Postcard-size

 Print postcard-sized (148x100mm, 5.8 x 3.9in) images
 on a Canon Selphy CP1200 and compatible photo printers

 Usage: print-selphy-postcard [--border] <file>

# Requirements

 This script requires ImageMagick, GNU sed and other text processing
 utilities, and CUPS.

# Configuration parameters:

## Printer name
 Set Wi-Fi printer name, as seen by CUPS.

 Corresponding printer entry in CUPS configuration should be something like:
 dnssd://Canon%20SELPHY%20CP1200._ipp._tcp.local/?uuid=<uuid>

 To produce that entry for a new printer, use CUPS printer autodetection
 (usually http://localhost:631 , Administration / Add Printer menu) while
 mDNS service discovery is enabled.

# License

 This program is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 2 of the License, or
 (at your option) any later version.
  
 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.
  
 You should have received a copy of the GNU General Public License
 along with this program.  If not, see <http://www.gnu.org/licenses/>.

# Credits

 This repo was forked from [abelits/canon-selphy-print](https://github.com/abelits/canon-selphy-print)

