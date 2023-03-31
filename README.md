# This one weird trick makes `plt.imshow()` irrelevant!!!1!!1!!
Never import matplotlib again!

```
. . .
mona_lisa_df = pd.DataFrame.from_records(hex_mona_lisa)
show_img(mona_lisa_df.style, pixel_size=8)
```
![Mona Lisa](https://github.com/dwisdom0/pandas-image-format/blob/main/mona_lisa.png)


# What?
Pandas has some formatting tools that are a little bit like Excel's "Conditional Formatting" feature.
I used those formatting tools to color each cell to match the hex string in the cell.
For example, a cell with the value `#639` would show up as a single pixel colored [`rebeccapurple`](https://meyerweb.com/eric/thoughts/2014/06/19/rebeccapurple/) (get a box of tissues ready before you click that link).

Et voilà.
