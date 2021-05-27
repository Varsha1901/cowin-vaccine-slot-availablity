# CoWIN vaccination slot availability using Python ( original code by Bhavesh Bhatt)

The [CoWin API](https://apisetu.gov.in/public/marketplace/api/cowin) currently states : "Further, these APIs are subject to a rate limit of 100 API calls per 5 minutes per IP". I tried deploying the Web Application but the API is blocking the request. You can easily run the web application on your machine by following the steps mentioned below.
&nbsp;

### Windows Users
1. Download the [appropriate version](https://www.anaconda.com/products/individual) of Anaconda
2. Follow the instructions on that page to run the installer.
3. Go to Start and Run Jupyter Notebook.
4. Click `New Notebook`, which should open a new page.

# Usage
- Clone the repository. using `! Git Clone https://github.com/bhattbhavesh91/cowin-vaccination-slot-availability.git `
- The tool only works with Indian IP addresses so disconnect your VPN if needed.
- Enter the command - `cd cowin-vaccination-slot-availability/`
- Install all the dependencies - `! pip3 install -r requirements.txt`
- Run Anaconda Promt (Run as Administrator) From Start Menu.
- Go to your Directory Eg `cd C:\Users\lenovo\Desktop\Jupyter Notebooks\2021\Cowin\cowin-vaccination-slot-availability`
- Run `streamlit run app.py`

-   You can now view your Streamlit app in your browser.

  Local URL: http://localhost:8501
  Network URL: http://192.168.1.7:8501
