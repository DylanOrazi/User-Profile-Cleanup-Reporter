User Profile Cleanup Reporter 

Project Overview:
User Profile Cleanup Reporter is a PowerShell automation project that scans common Windows user profile folders and generates cleanup reports. The tool identifies folder sizes, file counts, large files, old files, file type breakdown, and cleanup recommendations. 

Project Purpose:
The purpose of this project was to build a safe PowerShell reporting tool that helps identify possible storage cleanup opportunities without deleting, moving, or modifying any files. 

Tools Used: 
- PowerShell
- Windows File Explorer
- CSV reports 
- TXT summary reports 
- File system documentation 
- Project documentation 

Main Files: 
- User_Profile_Cleanup_Reporter.ps1 
- README.txt

Project Folders:
- Reports 

Folders Scanned: 
- Downloads 
- Desktop 
- Documents 
- Pictures
- Videos
- Music 

Reports Generated:
- Folder_Summary_[timestamp].csv 
- Large_Files_[timestamp].csv
- Old_Files_[timestamp].csv 
- File_Type_Breakdown_[timestamp].csv 
- Cleanup_Summary_Report_[timestamp].txt
- Cleanup_Reporter_Log_[timestamp].txt

Main Features:
- Scans common user profile folders 
- Calculates folder size 
- Counts files in each folder 
- Finds large files 
- Finds old files 
- Breaks down files by category 
- Creates cleaning recommendations 
- Exports multiple CSV reports 
- Creates a readable TXT summary report 
- Uses timestamps for report files 
- Does not delete, move, or modify files 

File Categories:
The script groups files into categories such as: 
- PDF
- Documents 
- Spreadsheets 
- Presentations 
- Images 
- Videos 
- Audio 
- Archives 
- Executables 
- Scripts 
- Other 
- No Extension 

Large File Detection:
The script identifies files over the configured large file threshold. This helps locate files that may be taking up significant storage space. 

Old File Detection: 
The script identifies files older than the configured age threshold. This helps locate files that may be candidates for review or archiving.

Cleanup Recommendations:
This tool provides recommendations based on folder size and file count. These recommendations help guide manual cleanup decisions.

Safety Note: 
This tool is report-only . It does not delete files, move files, rename files, or modify user data. Any cleanup actions must be done manually by the user after reviewing the reports. 

How to Run: 
1. Open PowerShell 
2. Navigate to the project folder 
3. Run the execution policy bypass command if needed:
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass  
4. Run the script:
   .\User_Profile_Cleanup_Reporter.ps1 
5. Review the generated reports inside the Reports folder. 

Testing: 
The script was tested successfully. CSV and TXT reports were generated, opened, and reviewed. No files were deleted or moved during testing. 

Skills Demonstrated 
- PowerShell scripting 
- File system scanning 
- Recursive folder analysis 
- CSV report 
- TXT report generation 
- File size calculations 
- Data-based file filtering 
- Object creation with PSCustomObject
- Error handling 
- Logging 
- Safe automation design 
- IT support reporting 
- Project documentation 

Project Value: 
This project is valuable because it demonstrates a practical IT support automation tool. It can assist users or technicians identify storage usage patterns and possible cleanup opportunities while keeping the process safe and non-destructive.    































