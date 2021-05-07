# TamaKOR.o
SMG1's complete KOR symbol map partially ported to US (NTSC-U).

---

Super Mario Galaxy's code is beautiful. It was originally written in C++ and was then compiled to PowerPC Assembly. All this assembly code (ASM) resides in the game's main.dol. Assembly code consists of relatively basic and small instructions and at its surface is somewhat difficult to read and understand.

A symbol map contains the names (as well as inputs) of the original C++ functions. Such a map is extremely useful when analyzing the game's code, as it gives insight into the purpose of each function. We are very fortunate to have an almost complete symbol map for the Korean (KOR) release of Super Mario Galaxy! However, most people don't _own_ the Korean release of Super Mario Galaxy....

This project attempts to remedy that by porting these symbols to the US release of Super Mario Galaxy. Therefore, anyone who owns that release of the game can use this symbol map to better analyze and explore Super Mario Galaxy's code.

---

Here's all 80 .a (archive) files, their lengths (that is, the number of symbols/functions in them), and the number of symbols that have been ported to RMGE01.map _(The totals may not be completely accurate due to the KOR map containing fraudulent auto-generated symbols)._

|KOR archive (.a) file| Length| Ported|
|---|---|---|
|libnw4r_ut.a|100|60|
|libnw4r_db.a|11|6|
|libnw4r_math.a|5|3|
|libnw4r_lyt.a|279|55|
|Animation.a|238|37|
|AreaObj.a|414|80|
|AudioLib.a|618|92|
|Boss.a|6667|44|
|Camera.a|1957|27|
|Demo.a|669|85|
|Effect.a|373|5|
|Enemy.a|8842|164|
|GameAudio.a|72|0|
|Gravity.a|223|0|
|LiveActor.a|968|123|
|Map.a|2601|27|
|MapObj.a|10923|279|
|NameObj.a|793|102|
|NPC.a|3941|112|
|Player.a|3016|729|
|RhythmLib.a|317|0|
|Ride.a|1659|0|
|Scene.a|592|54|
|Screen.a|4568|284|
|Speaker.a|88|0|
|System.a|2225|346|
|Util.a|4039|958|
|NWC24.a|167|0|
|JKernel.a|470|34|
|JSupport.a|36|17|
|JGadget.a|7|7|
|JUtility.a|162|23|
|J2DGraph.a|165|33|
|J3DGraphBase.a|953|13|
|J3DGraphAnimator.a|220|14|
|J3DGraphLoader.a|221|7|
|JMath.a|20|12|
|JParticle.a|252|6|
|gd.a|43|7|
|thp.a|33|0|
|tpl.a|4|2|
|wenc.a|1|1|
|rso.a|26|0|
|RVLFaceLib.a|275|0|
|net.a|6|0|
|nwc24.a|296|16|
|vf.a|452|0|
|JAudio2.a|1211|39|
|aralt.a|23|6|
|base.a|25|20|
|os.a|471|127|
|exi.a|29|22|
|si.a|20|10|
|db.a|7|3|
|vi.a|129|28|
|mtx.a|56|27|
|gx.a|277|292|
|dvd.a|280|76|
|ai.a|18|14|
|ax.a|14|3|
|axfx.a|25|9|
|mem.a|23|12|
|dsp.a|26|6|
|nand.a|108|36|
|sc.a|72|32|
|arc.a|15|7|
|esp.a|11|0|
|ipc.a|49|76|
|fs.a|36|20|
|pad.a|2|1|
|wpad.a|191|32|
|euart.a|7|3|
|usb.a|65|7|
|wud.a|208|30|
|bte.a|1272|0|
|Runtime.PPCEABI.H.a|43|16|
|MSL_C.PPCEABI.bare.H.a|230|65|
|TRK_Hollywood_Revolution.a|185|0|
|NdevExi2A.a|19|13|
|kpad.a|47|1|


If you port any symbols and want to add them here, please submit a pull request! It will be appreciated :)
