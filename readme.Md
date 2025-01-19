# Landmark Clustering Application

## Project Structure

## Server (FastAPI)

### Technologies Used
- FastAPI
- Python 3.8+
- OLA Maps API
- Vercel for deployment

### Setup
```bash
cd server
pip install -r requirements.txt

API_KEY=your_ola_maps_api_key
API Endpoints
POST /api/v1/clusters
Request body:
{
  "landmarks": ["landmark1", "landmark2"],
  "location": "city name",
  "proximity_threshold": 1.0
}


Client (React)
Technologies Used
React 18
Vite
Tailwind CSS
Vercel for deployment
Setup
cd client
npm install
Development
npm run dev