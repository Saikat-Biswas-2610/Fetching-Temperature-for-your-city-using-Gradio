# Fetching-Temperature-for-your-city-using-Gradio
Input your city name using Gradio and it will return the current temperature of your city

#import necessary packages
import requests
import json
import gradio as gr

#Gradio will take the input from the user as city name.
Once you click submit, it will return the temperature of the input city name by fetching live weather details from a different weather website.

If you input a wrong spelling of your city, it will tell you to learn to spell your city correctly. :P
