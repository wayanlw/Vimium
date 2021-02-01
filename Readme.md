Change of standard **Vimium keybindings**


## Installation
- Copy the content in the file **Vim_StandardCopy**
- Open vimium options
- paste it in the Vimium **Custom key mappings** window. 


## movement commands
map j scrollDown
map k scrollUp
map J scrollPageDown
map K scrollPageUp

## Back Forward
map h goBack
map l goForward

## Deactivates othe keys
map i enterInsertMode

## Close Reactivate tab
map w removeTab 
map W restoreTab

## Quick Tab Selection
map t Vomnibar.activateTabSelection
map T createTab

## Go to address
map ; Vomnibar.activate
map : Vomnibar.activateInNewTab

## Go to tabs
map U firstTab
map O lastTab
map u previousTab
map o nextTab

##open multiple links
map d LinkHints.activateModeWithQueue   # open multiple links
map D LinkHints.activateModeToOpenInNewTab

## Visit last visited tab
map p visitPreviousTab

## Closing tabs
map cr closeTabsOnRight
map cl closeTabsOnLeft
map co closeOtherTabs
