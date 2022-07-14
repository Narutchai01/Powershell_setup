oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/main/themes/montys.omp.json' | Invoke-Expression

Import-Module -Name Terminal-Icons
Import-Module -Name PSReadLine


Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView
Set-PSReadLineOption -EditMode Windows
-RequiredVersion 2.2.X
