# Zfifisitional-novo-editer-
from datetime import datetime
import time

while True:
    # Get the current date and time
    current_datetime = datetime.now().strftime("%Y-%m-%d %H:%M:%S")

    # Print the current date and time
    print("Current Date and Time:", current_datetime)

    # Wait for 1 second before updating the date and time
    time.sleep(1)
