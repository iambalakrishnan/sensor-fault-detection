## STEPS for EXPORT environment variable

### Step: 1 - Export the environment variable
```bash
export AWS_ACCESS_KEY_ID=<AWS_ACCESS_KEY_ID>

export AWS_SECRET_ACCESS_KEY=<AWS_SECRET_ACCESS_KEY>

export AWS_DEFAULT_REGION=<AWS_DEFAULT_REGION>

export MONGODB_URL="<mongo connection url>"

```

### Step: 2 - Run the application server
```bash
python app.py
```

### Step: 3 - Train application
```bash
http://localhost:8080/train

```

### Step: 4 - Prediction application
```bash
http://localhost:8080/predict
```
