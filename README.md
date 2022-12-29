## ipyvizzu

👉**what is ipyvizzu**

ipyvizzu is an animated charting tool for Jupyter, Google Colab, Databricks, Kaggle and Deepnote notebooks among other platforms. ipyvizzu enables data scientists and analysts to utilize animation for storytelling with data using Python. It's built on the open-source Javascript/C++ charting library Vizzu.

👉**Main features**:

- Designed with animation in focus;
- Defaults based on data visualization guidelines;
- Works with Pandas dataframe, while also JSON and inline data input is available;
- Auto scrolling feature to keep the actual chart in position while executing multiple cells

👉**Installing ipyvizzu**

- !pip install ipyvizzu

👉**Loading Pandas DataFrame in ipyvizzu**

The ipyvizzu library is 100% compatible with Pandas dataframes, so it is very simple to build graphs directly from data. To add a dataframe to a ipyvizzu chart, you need to declare a Data() object, and then add the dataframe to it:


