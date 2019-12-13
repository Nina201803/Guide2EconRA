## Python Tools and Tips

---

- Use both jupyter notebook and editor. They works best in different situations. The most commonly recommended editor is vscode.
- Use conda environment. The advance operation is to use virtual environment for different projects.
- Useful python packages:
  - Econ & Econometrics
    - linearmodels
    - quantecon
    - pyblp
    - interpolation
    - numecon
  - Plotting
    - altair
    - matplotlib-label-lines
    - folium
    - geopandas
  - Data
    - japandas
    - missingno
    - pandas-datareader
  - Web scrapping
    - requests-html
    - selenium
  - Others
    - panel
- The python files placed in the [snippets](/snippets) folder are some simple code and examples either homemade or stolen from someone else.
  - You can simply apply these snippets into your code.
  - Alternatively you can import them just like the one you installed through conda or pip. In order to do this, you need add the dir where you place your modules to `sys.path`. (see [here](https://stackoverflow.com/a/37008663) if you don't know how to do it).
  - Moreover you can make some module to be executed automatically whenever you launch the python kernel in a Jupyter notebook.
  - Note tha you can always try to write your own helpfyl modules.