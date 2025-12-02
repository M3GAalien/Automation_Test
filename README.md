# CodespaceTest
Testing github codespaces

<details>
  <summary>Click to expand</summary>

## Command to auto publish and commit code ##

`dotnet publish -c Release -r win-x64 -p:PublishSingleFile=true --self-contained true
mv ./Gaiia_Automation_Test/bin/Release/net8.0/win-x64/publish/Gaiia_Automation_Test.exe ./Program
git add .
git commit -m "Automated commit"
git push
git checkout main
git merge Michael
git add .
git commit -m "Automated commit"
git push origin main`

</details>

## List of keywords for generated messages ##

#ACCNUM - AccountNumber (123456)
#FNAME - FirstName      (John)
#LNAME - LastName       (Doe)
#PHONE - PhoneNumber    (123-456-7890)
#SUB - Subsciption      (500Mbps. for $75/Month)
#LOC - Address          (123 test, place, FL 12345, USA)
#TIME - InstallTime     (Tuesday Nov. 25th, 11:00am - 2:00pm)