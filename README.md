# 📊 Interactive Category Chart with Gradio and Plotly

This is a simple interactive data visualization project built using **Gradio**, **Plotly**, and **Pandas**. The app allows users to select a category (`A`, `B`, or `C`) from a dropdown and visualize the corresponding bar chart for `Value1` values.

## 🔧 Features

- ✅ Random synthetic dataset with 3 categories and 2 value columns
- ✅ Dynamic bar chart filtered by selected category
- ✅ Clean and modern UI using **Gradio**
- ✅ Visualizations powered by **Plotly**

## 🧠 Technologies Used

- `pandas` - Data manipulation
- `numpy` - Synthetic data generation
- `plotly.express` - Interactive data visualization
- `gradio` - Web app interface

## 🧪 How It Works

1. Generate a DataFrame with:
   - 100 entries
   - Randomly assigned categories (A, B, C)
   - Random values for `Value1` (integers) and `Value2` (floats)

2. When a user selects a category, a bar chart of `Value1` for that category is shown.
