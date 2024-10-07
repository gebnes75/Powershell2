# Powershell2
PS C:\> Get-History
 Id CommandLine                                                                                                           
 -- -----------                                                                                                           
  1 get location                                                                                                          
  2 Get-Location                                                                                                          
  3 Get-Location                                                                                                          
  4 Get-Host                                                                                                              
  5 New-Item -path temp itemdirectory                                                                                     
  6 New-Item -Path temp                                                                                                   
  7 Set-Location temp                                                                                                     
  8 get location                                                                                                          
  9 Get-Location                                                                                                          
 10 set-location pc                                                                                                       
 11 Get-ChildItem                                                                                                         
 12 set-location -path temp                                                                                               
 13 set-location temp                                                                                                     
 14 Get-Location                                                                                                          
 15 set-location -path temp                                                                                               
 16 Set-Location                                                                                                          
 17 Set-Location -path c:\                                                                                                
 18 Get-Location                                                                                                          
 19 set-location -path temp                                                                                               
 20 Get-ChildItem                                                                                                         
 21 Set-Location -Path C:\...                                                                                             
 22 Get-ChildItem -recurse                                                                                                
 23 set location                                                                                                          
 24 Get-Location                                                                                                          
 25 Get-ChildItem                                                                                                         
 26 Set-Location -Path FolderTest1                                                                                        
 27 Get-ChildItem                                                                                                         
 28 Set-Location                                                                                                          
 29 Set-Location -Path                                                                                                    
 30 Set-Location -Path c:\                                                                                                
 31 Get-ChildItem                                                                                                         
 32 New-Item -Path EvenFolder                                                                                             
 33 New-Item -Path c:\EvenFolder                                                                                          
 34 New-Item -ItemType File -Path c:\EvenFolder                                                                           
 35 New-Item -Path EvenFolder -ItemType Directory                                                                         
 36 New-Item -Path OddFolder -ItemType Directory                                                                          
 37 Get-ChildItem                                                                                                         
 38 Move-Item -Path File2 -Destination C:\EvenFolder                                                                      
 39 Move-Item -Path c:\FolderTest1\File2 -Destination C:\EvenFolder                                                       
 40 Move-Item -Path c:\FolderTest1\File4 -Destination C:\EvenFolder                                                       
 41 Move-Item -Path c:\FolderTest1\File6 -Destination C:\OddFolder                                                        
 42 Move-Item -Path c:\FolderTest2\File6 -Destination C:\OddFolder                                                        
 43 Move-Item -Path c:\FolderTest2\File8 -Destination C:\OddFolder                                                        
 44 Move-Item -Path c:\FolderTest2\File10 -Destination C:\OddFolder                                                       
 45 Move-Item -Path c:\FolderTest2\File9 -Destination C:\OddFolder                                                        
 46 Move-Item -Path c:\FolderTest2\File7 -Destination C:\OddFolder                                                        
 47 Move-Item -Path c:\FolderTest2\File5 -Destination C:\OddFolder                                                        
 48 Move-Item -Path c:\FolderTest1\File5 -Destination C:\OddFolder                                                        
 49 Move-Item -Path c:\FolderTest1\File3 -Destination C:\OddFolder                                                        
 50 Move-Item -Path c:\FolderTest1\File1 -Destination C:\OddFolder                                                        
 51 Move-Item -Path c:\OddFolder\File6 -Destination C:\EvenFolder                                                         
 52 Move-Item -Path c:\OddFolder\File8 -Destination C:\EvenFolder                                                         
 53 Move-Item -Path c:\OddFolder\File10 -Destination C:\EvenFolder                                                        
 54 Get-ChildItem -Path OddFolder                                                                                         
 55 Get-ChildItem -Path EvenFolder                                                                                        
 56 Get-History > historique.txt    
 PS C:\> Get-ChildItem -Path *Folder* -Recurse
   Répertoire : C:\EvenFolder
Mode                 LastWriteTime         Length Name                                                                     
----                 -------------         ------ ----                                                                     
-a----        30/09/2024     12:08              0 File10                                                                   
-a----        30/09/2024     12:04              0 File2                                                                    
-a----        30/09/2024     12:04              0 File4                                                                    
-a----        30/09/2024     12:08              0 File6                                                                    
-a----        30/09/2024     12:08              0 File8                                                                    
   Répertoire : C:\OddFolder
Mode                 LastWriteTime         Length Name                                                                     
----                 -------------         ------ ----                                                                     
-a----        30/09/2024     12:04              0 File1                                                                    
-a----        30/09/2024     12:04              0 File3                                                                    
-a----        30/09/2024     12:04              0 File5                                                                    
-a----        30/09/2024     12:08              0 File7                                                                    
-a----        30/09/2024     12:08              0 File9
