# Monitors Finding

</br>

### Installation
`pip install --no-cache-dir -r requirements.txt`

Create a `.env` file to store the:
`GEMINI_API_KEY=""`
`SERPER_API_KEY=""`
`SUPABASE_URL=""`
`SUPABASE_KEY=""`

### Run the GenAI app
`streamlit run app.py`

Access the application at http://localhost:8501

</br>

### Containerize GenAI app

+ Build the image:
`docker image build --no-cache -t eap-db-monitors:0.1 .`

+ Run the container:
`docker container run -d -p 8501:8501 -e GEMINI_API_KEY="" -e SERPER_API_KEY="" -e SUPABASE_URL="" -e SUPABASE_KEY="" eap-monitors:0.1`

Access the application at http://localhost:8501

</br>

__Note__: When running the container, you must provide your Google Gemini API KEY, the Serper API KEY, and the SUPABASE_URL SUPABASE_KEY as an environment variable.

</br>

### Create the following tables in your Supabase database:

</br>

</br>

</br>

</br>

</br>

</br>

</br>

</br>
