# MenuSettings Table
Table of the known size parameters

| Offset | Length | DataType          | Name                     |
|--------|--------|-------------------|--------------------------|
| 0x0    | 0x4    | MenuPage          | menuPage                 |
| 0x4    | 0x4    | int               | unk_multiplayerMirror    |
| 0x8    | 0x4    | MultiplayerMode   | multiplayerMode          |
| 0xc    | 0x4    | int               |                          |
| 0x10   | 0x4    | Gamemode          | gamemode                 |
| 0x14   | 0x4    | RaceSpeed         | raceSpeed                |
| 0x18   | 0x4    | Character         | character                |
| 0x1c   | 0x4    | int               | cup                      |
| 0x20   | 0x4    | int               | unk                      |
| 0x24   | 0x4    | int               | lastCharacter            |
| 0x30   | 0x4    | int               |                          |
| 0x38   | 0x4    | int               |                          |
| 0x3c   | 0x4    | int               |                          |
| 0x40   | 0x4    | int               |                          |
| 0x44   | 0x2    | ushort            |                          |
| 0x4c   | 0x4    | uint              |                          |
| 0x50   | 0x4    | int               |                          |
| 0x54   | 0x4    | int               |                          |
| 0x58   | 0x4    | int               |                          |
| 0x5c   | 0x4    | int               |                          |
| 0x60   | 0x4    | int               |                          |
| 0x64   | 0x4    | int               |                          |
| 0x68   | 0x4    | int               |                          |
| 0xb0   | 0x4    | int               |                          |
| 0xcc   | 0x4    | int               |                          |
| 0xd0   | 0x4    | int               |                          |
| 0xd4   | 0x4    | int               |                          |
| 0xd8   | 0x4    | int               |                          |
| 0x100  | 0x4    | int               |                          |
| 0x4ec  | 0x4    | int               | charcterSelectedTile     |
| 0x4fc  | 0x4    | int *             | unk_menuPageRelated      |
| 0x508  | 0x4    | int               | unk_ccRelatedPointer     |
| 0x5fc  | 0x4    | int               |                          |
| 0x600  | 0x4    | int               |                          |
| 0x6d0  | 0x4    | int               |                          |
| 0x6d4  | 0x2    | undefined2        |                          |
| 0x6d6  | 0x2    | undefined2        |                          |
| 0x6d8  | 0x4    | int               |                          |
| 0x6dc  | 0x4    | int               |                          |
| 0x6e0  | 0x4    | int               |                          |
| 0x6e4  | 0x4    | int               |                          |
| 0x6e8  | 0x4    | int               |                          |
| 0x6ec  | 0x4    | int               |                          |
| 0x6f0  | 0x4    | int               |                          |
| 0x6f4  | 0x4    | int               |                          |
| 0x6f8  | 0x4    | int               |                          |
| 0x6fc  | 0x4    | int               |                          |
| 0x700  | 0x4    | int               |                          |
| 0x704  | 0x4    | int               |                          |
| 0x708  | 0x4    | int               |                          |
| 0x70c  | 0x4    | int               |                          |
| 0x710  | 0x2    | undefined2        |                          |
| 0x712  | 0x2    | undefined2        |                          |
| 0x714  | 0x4    | int               |                          |
| 0x718  | 0x4    | int               |                          |
| 0x71c  | 0x4    | int               |                          |
| 0x720  | 0x4    | int               |                          |
| 0x724  | 0x4    | int               |                          |
| 0x728  | 0x4    | int               |                          |
| 0x72c  | 0x4    | int               |                          |
| 0x730  | 0x4    | int               |                          |
| 0x734  | 0x4    | int               |                          |
| 0x738  | 0x4    | undefined4        | unk_cupMirror            |
| 0x73c  | 0x4    | undefined4        | unk_unkMirror            |
| 0x740  | 0x4    | undefined4        |                          |
| 0x744  | 0x4    | undefined4        |                          |
| 0x748  | 0x4    | undefined4        |                          |
| 0x74c  | 0x4    | undefined4        |                          |
| 0x750  | 0x4    | undefined4        |                          |
| 0x7e4  | 0x4    | undefined4        |                          |
| 0x7e8  | 0x4    | int               |                          |
| 0x7ec  | 0x4    | undefined4        |                          |
| 0x7f0  | 0x2    | undefined2        |                          |
| 0x7f2  | 0x2    | undefined2        |                          |
| 0x7f4  | 0x4    | undefined4        |                          |
| 0x7f8  | 0x4    | undefined4        |                          |
| 0x7fc  | 0x2    | undefined2        | unk_trackSelectionFlags1 |
| 0x7fe  | 0x2    | undefined2        | trackSelectionFlags      |
| 0x800  | 0x4    | undefined4        |                          |
| 0x804  | 0x4    | undefined4        |                          |
| 0x808  | 0x4    | undefined4        |                          |
| 0x80c  | 0x2    | undefined2        | unk_trackSelectionFlags2 |
| 0x80e  | 0x2    | undefined2        | unk_trackSelectionFlags3 |
| 0x810  | 0x4    | undefined4        |                          |
| 0x814  | 0x4    | undefined4        |                          |
| 0x818  | 0x4    | undefined4        |                          |
| 0x81c  | 0x4    | undefined4        |                          |
| 0x820  | 0x4    | undefined4        |                          |
| 0x824  | 0x4    | undefined4        |                          |
| 0x828  | 0x4    | undefined4        |                          |
| 0x82c  | 0x2    | undefined2        | unk_trackSelectionFlags4 |
| 0x82e  | 0x2    | undefined2        | unk_trackSelectionFlags5 |
| 0x830  | 0x4    | undefined4        |                          |
| 0x834  | 0x4    | undefined4        |                          |
| 0x838  | 0x4    | undefined4        |                          |
| 0x83c  | 0x4    | undefined4        |                          |
| 0xc40  | 0x4    | undefined4        |                          |
| 0xc44  | 0x4    | undefined4        |                          |
| 0xc48  | 0x4    | undefined4        |                          |
| 0xc4c  | 0x2    | undefined2        |                          |
| 0xc4e  | 0x2    | undefined2        |                          |
| 0xc50  | 0x4    | undefined4        |                          |
| 0xc54  | 0x4    | undefined4        |                          |
| 0xc58  | 0x4    | undefined4        |                          |
| 0xc5c  | 0x4    | undefined4        |                          |
| 0xc60  | 0x4    | undefined4        |                          |
| 0xc64  | 0x4    | undefined4        |                          |
| 0xc68  | 0x4    | undefined4        |                          |
| 0xc6c  | 0x4    | int               |                          |
| 0xc70  | 0x4    | int               |                          |
| 0xd34  | 0x4    | int               |                          |
| 0xd38  | 0x4    | undefined4        |                          |
| 0xd3c  | 0x4    | undefined4        |                          |
| 0xd40  | 0x4    | undefined4        |                          |
| 0xd44  | 0x4    | uint              |                          |
| 0xd48  | 0x4    | uint              |                          |
| 0xd4c  | 0x4    | undefined4        |                          |
| 0xd54  | 0x4    | undefined4        |                          |
| 0xd58  | 0x4    | undefined4        |                          |
| 0xd5c  | 0x4    | undefined4        |                          |
| 0xd60  | 0x2    | undefined2        |                          |
| 0xd62  | 0x2    | undefined2        |                          |
| 0xd64  | 0x2    | undefined2        |                          |
| 0xd66  | 0x2    | undefined2        |                          |
| 0xd68  | 0x4    | undefined4        |                          |
| 0xd6c  | 0x4    | undefined4        |                          |
| 0xd70  | 0x4    | undefined4        |                          |
| 0xd74  | 0x4    | uint              |                          |
| 0xd78  | 0x4    | int               |                          |
| 0xd7c  | 0x4    | uint              |                          |
| 0xd80  | 0x4    | int               |                          |
| 0xd84  | 0x4    | undefined4        |                          |
| 0xd88  | 0x4    | int               |                          |
| 0x1088 | 0x4    | uint              |                          |
| 0x109c | 0x4    | int               |                          |
| 0x10a0 | 0x4    | undefined4        |                          |
| 0x112c | 0x4    | int               | unk_hasSpecialUnlocked   |
| 0x1130 | 0x8a   | UnkTrackDataTable | unkTrackDataTable        |
| 0x11c0 | 0x23   | unk_dataStruct    |                          |
| 0x11e3 | 0x1    | char              |                          |
| 0x11e4 | 0x4    | int               | trackPage                |
