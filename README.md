# WebTraffic-Analyzer-Python 🚀


**Analisi traffico website con Python. Dashboard metriche visite, bounce rate, user journey.**

[![Python](https://img.shields.io/badge/Python-3.11+-blue)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-green)](https://pandas.pydata.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-orange)](https://streamlit.io)


<br> 

## 📖 Descrizione
Scraping log server/accessi Google Analytics → ETL → Dashboard interattivo.
- Metriche: Visite uniche, bounce rate, top pagine/UTM
- Visualizzazioni: Trend tempo, heatmap referrer
- Deploy: Streamlit/Netlify

<br>

**Obiettivo CV:** Web analytics + data engineering per ruoli growth/data analyst. 

<br>

## 🛠 Tech Stack
- **Backend:** Python, Pandas, Requests/BeautifulSoup
- **Visual:** Plotly, Streamlit, Matplotlib
- **Dati:** Log server, GA4 API, CSV/JSON
- **Deploy:** Netlify, GitHub Pages

  <br>

## 🚀 Installazione & Demo
```bash
git clone https://github.com/Suzuka90/WebTraffic-Analyzer-Python.git
pip install -r requirements.txt
streamlit run app.py
```

<br>

## 📊 Risultati Esempio
**Metriche Sito Reale (tuoi dati):**

<span>
  <img src="top_clicks.png" width="400" alt="Top Clicked Pages Analytics">
  <img src="trafficoPerOra.png" width="400" alt="Traffico per Ora">
</span>

<br> <br>

<div align="center"> 
  
  | Metrica       | Valore   |
  |---------------|----------|
  | Visite Totali | 12,847  |
  | Bounce Rate   | 42.3%   |
  | Top Pagina    | /blog   |
  | Top Referrer  | Google  |
  
</div>

<br>

## 💡 Apprendimenti
- Parsing log Apache/Nginx → Pandas DataFrame
- GA4 API integration + UTM tracking
- Prossimo: Real-time analytics con WebSocket

  <br>

## 📄 Licenza
MIT. <br>

---
**© 2026 Suzuka90** | **Private Access**
