# scatterplot
creating a scatterplot

# You’ve volunteered to add titles to the plots. You begin with a scatterplot. 

# the first part of your code chunk is:
ggplot(data = trimmed_flavors_df) +
geom_point(mapping = aes(x = Cocoa.Percent, y = Rating)) +

# To add the title Recommended Bars to your plot:
labs(title = “Recommended Bars”)

# Next, you create a new scatterplot to explore the relationship between different variables. You want to save your plot so you can access it later on. You know that the ggsave() function defaults to saving the last plot that you displayed in RStudio, so you’re ready to write the code to save your scatterplot. 

# First two lines of code are:
ggplot(data = trimmed_flavors_df) +
geom_point(mapping = aes(x = Cocoa.Percent, y = Rating)) 

# to save your plot as a png file with chocolate as the file name
ggsave(“chocolate.png”)

# Pro tip: You want to record and share every step of your analysis, let teammates run your code, and display your visualizations. 
You can create an R markdown notebook to document your work.
