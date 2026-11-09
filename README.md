# More Shambler Xenotypes

Standalone content split out of Too Many Mods (core `1.6/Patches/AA3B_ShamblerXenotype.xml`, setting
`TMM_MoreShamblerXenotypes`, default on).

- Anomaly's shamblers get a xenotype set: vanilla Biotech xenotypes plus those of Big and Small, Alpha Genes, Det's
  Xenotypes, Rimsenal, VRE, Geist, Rim-Elves, Rim-Gnoblins, Goji's Merren and Biotech Expansion, each entry gated on its mod.
- With Alpha Genes, a few rarer entries are added (Hive Queen, Tiamat, Devilpuff). Big and Small's corrupted titan was removed.
- With Cybranian - Anomaly Ghosts, ghosts get a similar spread (name check; packageId unknown).

Requires Anomaly and Biotech. The VQE Deadlife pallet tweak that sat in the same file went to MMMM_Rebalances-Other.

With Shambler Variants (dorbo.shamblervariants) installed, the vanilla xenotypes (all but Baseliner) and ten modded ones that mod uses
(Stoneborn, Avaloi, Brawnum, Saurid, Keshig, Geist, Venator, Half-foot, Insector, Buzzer) are taken out of the
ordinary shambler list (`1.6/Mods/ShamblerVariants`), because that mod makes each of them a special variant. Its eight
variant pawn kinds set their own xenotype list (`Inherit="False"`), so this mod never changes them.

`1.7/` is a copy of `1.6/` and `<v1.7>` mirrors `<v1.6>` in `loadFolders.xml`; change both when editing a patch.
