# k4webSmb

# SMB Web Exploit by kader11000

## How to Run

1. Make sure you have Python 3 and Flask installed.
2. Also make sure CrackMapExec is installed and accessible via terminal.
3. Replace <YOUR_IP> in the script with your local IP address (for file delivery).
4. Add your targets to `targets.txt` in this format:
   ```
   HostName1,192.168.1.10
   HostName2,192.168.1.15
   ```
5. Run the script:
   ```bash
   python3 smb_web_exploit.py
   ```
6. Access the web interface at:
   ```
   http://localhost:5000
   ```

## Files

- `smb_web_exploit.py`: The main script.
- `targets.txt`: Target list file.
