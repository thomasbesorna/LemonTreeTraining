# LemonTreeTraining

LemonTree Training Project vom 13.12.2022


## Setup Local Git Repository

### Git Repos clonen

+  `git clone https://github.com/thomasbesorna/LemonTreeTraining`

### LFS aktivieren und für .QEAX Dateien

+  `git lfs install`
+  `git lfs track "*.qeax"`

## EA-Repos Datei hinzufügen

+  `git add TrainerDemoModel.qeax`


## Recommendations

+  Compare two Commits be shure that the EA Model is closed!
+  https://github.com/lieberlieber/LemonTree.Pipeline.Tools

## Vorschläge

+  EA-Addin [Commit and Push]: the is a time delay between starting Commit and getting the confirmation for the Commit, the user don't know that the processing is going on; if you click in between into the EA Window the LT Dialog (with confirmation) is not shown because it is behind the "active" EA Window; therefore a modal "Processing" dialog would be fine.

+  Upgrade from LT-2 to LT-3: at LT-2 environment no SmartGit client was installed; now first the SmartGit client was installed and afterwards the LT-3 was installed ... I think the SmartGit support was not activated during the LT-3 installation - but I'm not really sure.

+  Save the last used size and position of the LT main/compare window; move a new opened LT window 10 points left and down.
