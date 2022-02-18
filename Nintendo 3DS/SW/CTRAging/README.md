# CTRAging

## Information
---
CTRAging is a piece of software that tests all hardware aspects of CTR units. All CTR, SPR, KTR, FTR, RED, and JAN units at one point in their life have run CTRAging or it's respective derivitive on them. Usually, CTRAging deletes itself before preparing the CTR unit for retail. This, however, isn't always the case.

There are derivitives of this software for each CTR hardware revision, including SPR, KTR, FTR, RED, and JAN. The software is mostly identical, with a few tests added / removed to better account for the hardware. For this reason, I will consider all of these derivitives to be "CTRAging".

## Speculation
---
- If someone can combine a valid RomFS with Forest of Illusion's dump, O3DS CTRAging *MAY* be recoverable.

## Sources
---
- Nintendo Gigaleak
    - Path (Dump): ``3ds_manu.7z\KTR_Aging_Import_Program_ver.580_3833_9.12_Release.master.7z\KTR_Aging_Import_Program_ver.5.80_3833_9.12_Release.master.csu\content0.game\romfs\cia\Aging.cia``
    - Path (Images): ``Documents.7z\Documents\セキュリティチーム運営\プロジェクト\INDY検討\eFuse検討\ＣＴＲ本体電気検査仕様書.pdf``
- Publicly Acquired (All Units)
    - Note: Since all CTR units at one point in their life-cycle have run this app, it is possible to recover pieces of the software before the first power on. To date, no CTR unit has been recovered with a full intact dump of the software on it. There have been full dumps of KTRAging recovered from KTR units. However, Forest of Illusion's CTR unit was acquired before the factory process finished, thus recovering a nearly complete copy of the software.
- Publicly Acquired (Forest of Illusion)
    - Note: The CTR version of the software was released by Forest of Illusion in early 2022. The dump is mostly intact, but the RomFS in this dump is corrupt, rendering the app un-bootable.
    - URL: https://twitter.com/forestillusion/status/1484328426131836930