#### cli-marketing-website
Marketing website for my CLI Teleconsultation Tool
### Steps to Download, Install, and Run RuralHealth CLI
1.Download the Binary for Your Platform
2.Go to the Releases section of the project on GitHub.
## Download the appropriate binary for your operating system:
For Linux: rural_health_cli-x86_64-unknown-linux-gnu
For Windows: rural_health_cli-x86_64-pc-windows-gnu.exe
For macOS: rural_health_cli-x86_64-apple-darwin
Make the Binary Executable (Linux/macOS)

### After downloading, open a terminal and navigate to the download directory.
Run the following command to make the binary executable:
chmod +x rural_health_cli-x86_64-unknown-linux-gnu
Run the CLI
Linux/macOS:
./rural_health_cli-x86_64-unknown-linux-gnu
Windows:
Double-click rural_health_cli-x86_64-pc-windows-gnu.exe or run it in Command Prompt:
rural_health_cli-x86_64-pc-windows-gnu.exe
Use the Commands
View available commands:
bash
./rural_health_cli --help
## Example commands:
# Check Symptoms:
bash
./rural_health_cli triage --symptoms fever,cough
# Book a Teleconsultation:
bash
./rural_health_cli book --name "John Doe" --phone "123456789"
# View Health Tips:
bash
./rural_health_cli tips
# Request Supplies:
bash
./rural_health_cli supplies --item "First Aid Kit"
