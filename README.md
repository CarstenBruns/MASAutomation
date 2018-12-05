# MASAutomation

Welcome to my Citrix Application Delivery Management (ADM) (formally: NetScaler Management and Analytics (MAS)) repository.

My repository keeps track of all Citrix ADM (formally: NetScaler MAS) Configuration Jobs I have created during my many adventures to automate NetScaler deployments and configurations.

This repository will contain the different custom ADM Configuration Jobs to support automated enrollment for Citrix ADC (formally: NetScaler) deployments and configurations where the ADM is your centralized management system.

What you'll get:

- Files beginning with a number 01_cj_:
    Baseline configuration for Citrix ADM. Make sure to use the right order (from 01_ upwards)

- csv files:
    Example input files for variables I used within my config jobs
    
- Files beginning with zz_cj_:
    Examples for additional configurations you might need (e.g. pbrs)
    
To import all the conf jobs in your Citrix ADM you just need to choose the right section.

    For Configuration Jobs use ADM -> Networks -> Configuration Jobs -> Configuration Templates -> Import

So right now it holds the demo scripts from my Citrix Synergy and Citrix TEX presentations to give you a head start at building your own automated configs for Citrix ADM to centralize your ADC infrastructure management!

If you are looking for the more automation stuff (like Stylebooks) and impressive PowerShell scrips that were shown during the presentations, please visit Esther Barthels GitHib repository at https://github.com/cognitionIT/NetScalerMAS to ensure you get the latest versions of those files!
