# github-actions-flask

### Steps to Download and Run the app

1. **Clone the Repository:**

     ```bash
     git clone https://github.com/faialotaibi/github-actions-app.git
     ```

2. **Navigate to the Project Directory:**
   ```bash
   cd github-actions-app
   ```

3. **Set Up a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows
   ```

4. **Install Required Packages:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Application:**
   ```bash
   flask run
   ```

6. **Access the App:**
   
   ```
   http://localhost:5000
   ```
7. **Run tests:**
   
   ```
   pytest
   ```
### Build and Run the Docker Images

1. Build image

```
docker build -t your-image-name .
```

2. 
```
docker run -p 5000:5000 your-image-name
```
# flask-github-actions