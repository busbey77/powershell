# Define the file path
$filePath = "/tmp/example.txt"

# Create a new file
New-Item -Path $filePath -ItemType File

# Write content to the file
"Hello, this is a sample text written to the file." | Out-File -FilePath $filePath

# Read content from the file
$content = Get-Content -Path $filePath
Write-Output "Content of the file:"
Write-Output $content

# Append more content to the file
"Additional text appended to the file." | Out-File -FilePath $filePath -Append

# Read the updated content from the file
$newContent = Get-Content -Path $filePath
Write-Output "Updated content of the file:"
Write-Output $newContent

# Delete the file
Remove-Item -Path $filePath
Write-Output "File deleted successfully."
