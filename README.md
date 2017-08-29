# stunnel
Stunnel is a proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the programs' code. Its architecture is optimized for security, portability, and scalability (including load-balancing), making it suitable for large deployments.

Stunnel uses the OpenSSL library for cryptography, so it supports whatever cryptographic algorithms are compiled into the library. It can benefit from the FIPS 140-2 validation of the OpenSSL FIPS Object Module, as long as the building process meets its Security Policy. A scanned FIPS 140-2 Validation Certificate document is available for download on the NIST web page. The Windows binary installer is compiled with FIPS 140-2 support. The FIPS mode of operation is no longer enabled by default since stunnel 5.00.

Stunnel is a free software authored by Michał Trojnara. Although distributed under GNU GPL version 2 or later with OpenSSL exception, stunnel is not a community project. We retain the copyright of the source code. Please contact us for commercial support or non-GPL licenses. Free, community-based support is also available via stunnel-users mailing list.

stunnel license (see COPYRIGHT.GPL for detailed GPL conditions)

Copyright (C) 1998-2017 Michal Trojnara

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, see <http://www.gnu.org/licenses>.

Linking stunnel statically or dynamically with other modules is making a combined work based on stunnel. Thus, the terms and conditions of the GNU General Public License cover the whole combination.

In addition, as a special exception, the copyright holder of stunnel gives you permission to combine stunnel with free software programs or libraries that are released under the GNU LGPL and with code included in the standard release of OpenSSL under the OpenSSL License (or modified versions of such code, with unchanged license). You may copy and distribute such a system following the terms of the GNU GPL for stunnel and the licenses of the other code concerned.

Note that people who make modified versions of stunnel are not obligated to grant this special exception for their modified versions; it is their choice whether to do so. The GNU General Public License gives permission to release a modified version without this exception; this exception also makes it possible to release a modified version which carries forward this exception.