# colorist-guide
user guide for the colorist library in python.

# Copy and run this to see all 256 colors on your phone
from colorist import Color

for i in range(256):
    print(f"{Color.index(i)}{i:3}{Color.OFF}", end=" ")
    if (i + 1) % 10 == 0:
        print() # New line every 10 colors
