# Release 1.6.2 (versionCode 10)

Upload `Dragon-Slots-1.6.2-vc10-release.aab` to the Play Console. Upload `mapping-vc10.txt` if the console does not import the embedded R8 mapping automatically. `upload-certificate.pem` is the public certificate for Play App Signing / upload-key registration.

The corrective build keeps neutral player-facing terminology and rebuilds the
gameplay HUD with separate aligned `COST` and `SCORE` panels. It also widens the
top balance counter and reserves a stable six-slot number area, preventing labels,
values, and decorative endcaps from overlapping.

The bundle was produced by the release build with R8 enabled and verified as JAR-signed. File hashes are recorded in `SHA256SUMS.txt`.
