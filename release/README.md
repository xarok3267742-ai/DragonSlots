# Release 1.6.1 (versionCode 9)

Upload `Dragon-Slots-1.6.1-vc9-release.aab` to the Play Console. Upload `mapping-vc9.txt` if the console does not import the embedded R8 mapping automatically. `upload-certificate.pem` is the public certificate for Play App Signing / upload-key registration.

The corrective build replaces player-facing `BET`, `WIN`, `PAYS`, and `PAYTABLE`
terminology with `COST`, `SCORE`, and `REWARDS`, and separates the label/value
bands in the compact meter so the text no longer overlaps.

The bundle was produced by the release build with R8 enabled and verified as JAR-signed. File hashes are recorded in `SHA256SUMS.txt`.
