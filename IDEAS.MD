Soo... Hi mintylemon

Here's what Im thinking:
3 parts

1. The storage file (.sgma) - SeGMent Archive
* The cut files in little pieces, does NOT include metadata.
* Also includes some data such as file hash for correspondence with part 2
* Segement index (This can be baked into the file hash. FILE HASHES MUST BE UNIQUE)

2. The metadata file (.segm) - SEGment Metadata
* Contains a unique device identifier
* Contains a hash for correspondence with part 1 
* Has the metadata from original file
* Basically tells part 3 how to rebuild file, what file type it is etc

3. The Application
* Intakes a directory/folder with all of the parts and the segment metadata to rebuild the file
* OR
* Takes a large file and separate it.
* SHOULD LOOK LIKE KEKA. IF YOU DO NOT KNOW WHAT KEKA LOOKS LIKE: https://www.keka.io/en/
* You can download from the little download button, not from the App Store, for free