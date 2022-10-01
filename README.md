# scatterplot
creating a scatterplot

# You’ve volunteered to add titles to the plots. You begin with a scatterplot. 

# the first part of your code chunk is:
ggplot(data = trimmed_flavors_df) +
geom_point(mapping = aes(x = Cocoa.Percent, y = Rating)) +

# To add the title Recommended Bars to your plot:
labs(title = “Recommended Bars”)
