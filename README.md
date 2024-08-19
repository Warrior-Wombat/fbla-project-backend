# FBLA Backend Project Submission

## Description
This is the backend for our FBLA project submission. Installation instructions are down below.

## Installation

### Prerequisites
- Python 3.x
- Pip (Python package manager)
- Virtualenv (optional, but recommended)

### Setting Up a Virtual Environment (Optional)
Create a virtual environment in your project directory:
```bash
python -m venv venv
```

### Activating the Virtual Environment
On Windows:
```bash
.venv\Scripts\activate
```

On MacOS:
```bash
source venv/bin/activate
```

### Installing Requirements

Install all neccessary dependencies by running:
```bash
pip install -r requirements.txt
```

### Configure .env Variables (a lot!)

```bash
FLASK_SECRET_KEY=xxx
JWT_SECRET_KEY=xxx
JWT_ACCESS_TOKEN_EXPIRES=xxx
JWT_REFRESH_TOKEN_EXPIRES=xxx
CLIENT_ID=google-client-id
CLIENT_SECRET=google-client-secret
REDIRECT_URI=google-redirect-uri
AUTH_URI=google-auth-uri
TOKEN_URI=google-auth-token-uri
USER_INFO=google-user-info
ASSISTANT_ID=openai-assistant-id
MONGODB_URI=mongodb-uri
ATLAS_API_KEY=mongo-atlas-key
ATLAS_GROUP_ID=mongo-atlas-group-id
ATLAS_CLUSTER_NAME=atlas-cluster-name
OPENAI_API_KEY=openai-api-key
FOURSQUARE_API_KEY=foursquare-api-key
IBM_API_KEY=ibm-api-key
IBM_BUCKET_NAME=ibm-cos-bucket
IBM_SERVICE_INSTANCE_ID=ibm-cron-job-id
IBM_AUTH_URL=ibm-token-id
IBM_ENDPOINT_URL=ibm-s3-endpoint
SENDING_EMAIL=your-sending-email
SENDING_EMAIL_PASSWORD=sending-app-password
RECEIVING_EMAIL=your-receiving-email
ELEVENLABS_API_KEY=elevenlabs-api-key
VOICE_ASSISTANT_PROMPT=openai-transcription-prompt
```
