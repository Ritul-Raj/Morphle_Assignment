```markdown
# Flask System Monitor (htop Endpoint)

This project is a Flask-based web application that displays system information, including the system username, server time in IST, and the output of the `top` command at the `/htop` endpoint. It is designed to be deployed on a GitHub Codespace.

## Features

- Displays system username.
- Shows current server time in IST.
- Fetches and displays the `top` command output.
- Runs on a public GitHub Codespace with a publicly accessible `/htop` endpoint.

## Setup and Deployment

### **1. Create a GitHub Codespace**
- Fork this repository or create a new one.
- Open the repository in a new GitHub Codespace.

### **2. Install Dependencies**
Inside the Codespace terminal, run:

```bash
pip install flask pytz
```

### **3. Run the Flask Application**
Start the Flask app:

```bash
python app.py
```

### **4. Expose Port**
- In the Codespace environment, ensure that **port 5000** is publicly accessible.

### **5. Access the Endpoint**
- Open the browser and visit:

  ```
  http://<your-codespace-url>:5000/htop
  ```

## Example Output

When visiting `/htop`, the webpage will display:

```
Name: Ritul Raj
Username: <system username>
Server Time (IST): 2024-10-18 17:07:27 IST
Top Output:
(top command output here)
```

## Author

**Ritul Raj**
```

This keeps the README concise while maintaining all necessary details. Let me know if you need any modifications! 🚀
