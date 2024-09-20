# Symbols
This is my list of all of the symbols in the game. Currently the data type is not included, but it will be added in the future if I find a way.

## Labels
My list of known data labels. This list will expand over time.
| **Name**                         | **Location** |
|----------------------------------|--------------|
| **title_sDriversBgTilesBuf**     | 02010400     |
| **gTempBuffer**                  | 02025400     |
| **gMainFrmHeap**                 | 0202a400     |
| **Unk_ReturnToMenu**             | 0203ebe4     |
| **gMenuSettings**                | 0203ebe8     |
| **Unk_ButtonHeldRelated**        | 030001b0     |
| **gFlashMaxTime**                | 030023e0     |
| **PollFlashStatus**              | 030023e4     |
| **sTimerNum**                    | 030023e8     |
| **sTimerCount**                  | 030023ea     |
| **gFlashTimeoutFlag**            | 030023ec     |
| **sTimerReg**                    | 030023f0     |
| **sSavedIme**                    | 030023f4     |
| **EnabledInterruptsBuffer**      | 030023f8     |
| **col_sCpoiStartIndicesPassive** | 03002ca0     |
| **gSceneState**                  | 03002e20     |
| **byte_3002E28**                 | 03002e28     |
| **dmaq_sHeap**                   | 030048a0     |
| **gKeyTriggerBuf**               | 03004ea0     |
| **col_sCpoiStartIndicesActive**  | 03004eb0     |
| **gKeyBuf**                      | 03004f30     |
| **gKeyRepeatTriggerBuf**         | 03004f48     |
| **sio2_sKeyBuf**                 | 03004f58     |
| **gIrqTable**                    | 03004f80     |
| **IRQ_VBLANK_HANDLER**           | 03004f88     |
| **gSoundInfo**                   | 03005ca0     |
| **gMPlayJumpTable**              | 03006720     |
| **gCgbChans**                    | 030067b0     |
| **gMPlayMemAccArea**             | 030069f0     |
| **SongTable**                    | 08102498     |

## Functions
List of functions. Usefull in ghidra or similar programs.
| **Name**                         | **Location** |
|----------------------------------|--------------|
| **title_main**                   | 080001d8     |
| **title_main**                   | 08000e6c     |
| **SinglePlayerMenu_Main**        | 080021cc     |
| **ModeSelection**                | 08004860     |
| **CharacterSelect**              | 08007138     |
| **FadeScreenMaybeLoadData**      | 0800a8f0     |
| **TrackSelect**                  | 0800af94     |
| **TrackSelectContinued**         | 0800b294     |
| **CheckInputs**                  | 0800b70c     |
| **unk_CalledALot**               | 0800c422     |
| **something_main**               | 0802d0dc     |
| **RecalculateInput**             | 0802d398     |
| **VblankUpdate**                 | 0802d61c     |
| **unk_calloc**                   | 0802d6b8     |
| **sio2_stop**                    | 0802dc44     |
| **Unk_VramRelated**              | 0802e6c4     |
| **unk_setVramAddrs**             | 080303e4     |
| **unk_GetSomeInteruptThing**     | 08030434     |
| **LoadTrack**                    | 08031468     |
| **GetTrackAddressOrSomeShit**    | 08031990     |
| **GetTrackOffsetMKSC**           | 08033bac     |
| **GetTrackOffsetSMK**            | 08033bbc     |
| **playTrack_main**               | 0805167c     |
| **m4aSoundVSync**                | 0805f850     |
| **m4aSoundInit**                 | 0805fe9c     |
| **m4aSoundMain**                 | 0805ff14     |
| **CPUFastSet**                   | 0806134c     |
| **CPUSet**                       | 08061350     |
| **VblankIntrWait**               | 08061388     |
| **ModifyInterrupts**             | 0806261c     |
