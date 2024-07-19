1757
1758
1759
1760
1761
1762
1763
1764
1765
1766
1767
1768
1769
1770
1771
1772
1773
1774
1775
1776
1777
1778
1779
1780
1781
1782
1783
1784
1785
1786
1787
1788
1789
1790
1791
1792
1793
1794
1795
1796
1797
1798
1799
1800
1801
1802
1803
1804
1805
1806
1807
1808
1809
1810
1811
# DATA-SCIENCE-ARCHITECTURE-AI-and-ML
     xlab = "",
     ylab = "Volume",
     pch = 21, col = 4, bg = 4,
     family = "Algerian") # We are setting the "Algerian" font
Add Windows fonts with extrafont package in R


The same will apply for a ggplot2 chart:

# install.packages("ggplot2")
library(ggplot2)

ggplot(trees, aes(1:length(Volume), Volume)) +
      ggtitle("Custom fonts in ggplot2") +
      geom_point(col = 4) + 
      xlab("") +
      theme(text = element_text(family = "Algerian")) # Custom font
Use custom fonts in R ggplot2

# For charts that don't have an explicit option you have to work with the layouts
# Save the current graphical parameters
op <- par(no.readonly = TRUE)

# Set the font globally
par(family = "Algerian") # Specify the name of the font

# Create the histogram
hist(trees$Height,
     main = "All Fonts",
     ylab = "Frequency",
     xlab = "",
     col = 4)

# Restore the graphical parameters
on.exit(par(op))
# dev.off()

********** bonus   ********************
# Adding a Google Font
Google Fonts can be added with the font_add_google function of the package. For instance, if you want to add the Pacifico font you can type:

Load Pacifico font from Google Fonts
# install.packages("showtext")
library(showtext)

# You will need to have internet connection
# If you restart R you will need to execute this code again to use the font
font_add_google(name = "Pacifico",   # Name of the font on the Google Fonts site
                family = "pacifico") # Name you want to use to call the font






Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
