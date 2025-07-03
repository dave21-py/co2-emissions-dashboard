# CO2 Emissions dashboard

<p align="center">
<img src="logo.png"
width="400">
</p>

  ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaFX](https://img.shields.io/badge/javafx-%23FF0000.svg?style=for-the-badge&logo=javafx&logoColor=white) <img src="https://img.shields.io/badge/-HuggingFace-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black" /> <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white" /> <img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" /> <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" />  


## ❔Overview




## 👀 Demo

🎬 [Watch the demo]()


### ✨ Dashboard Screenshots

<p align="center">
<img src="demo1.png"
width="400">
</p>
<p align="center">
<img src="demo2.png"
width="400">
</p>


#### System Requirements

> Both MacOS and Windows supported.


## Code

### 🛠️ Environment Setup

```bash
# Clone the repo
git clone https://github.com/dave21-py/co2-emissions-dashboard.git
cd co2-emissions-dashboard

# Python virtual environment
python3 -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt

# Build the data (optional – CI refreshes it nightly)
python etl.py   # writes scores.csv

# Launch the dashboard
streamlit run app.py

```

## ✨ Credits

> + David Geddam [github.com](https://github.com/dave21-py)


## 🚀 Citation

If you find our work useful, please consider citing:

```
@software{geddam2025apacllmdashboard,
  title  = {Co2 Emissions dashboard},
  author = {David Geddam},
  year   = {2025},
  url    = {https://github.com/dave21-py/co2-emissions-dashboard.git}
}
```

## 📭 Contact

For any questions, please raise a concern or contact us at
+ David Geddam [linkedin.com](https://www.linkedin.com/in/david-geddam/)
