# mesa_rebuild
rebuilt Mesa to include -Dvideo-codecs=h264dec,h264enc,h265dec,h265enc,vc1dec \ (patented codecs being removed by Fedora.


Since the recent announcement that Fedora is removing h264dec,h264enc,h265dec,h265enc,vc1dec from Mesa which has the effect of removing hardware encoding/decoding. This rpm is based on F37 mesa source rpm and modified to include the codecs.

This RPM was built for Fedora 36 and since the official mesa version for fedora is 22.1.7-1 these RPM's can be installed as an upgrade.
