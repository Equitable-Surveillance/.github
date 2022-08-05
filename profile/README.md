# Equitable Surveillance    

<img width="467" alt="Screen Shot 2022-08-01 at 11 12 42 AM" src="https://user-images.githubusercontent.com/57039578/182181705-447fcdbc-ec22-4fbf-a641-73b0164a403b.png">


The equitable surveillance team is addressing the social justice issue of unlawful interactions which involve police officers. 
Using video/audio from the interaction as input, our platform uses NLP, Image Analysis, and Cloud Computing to produce a summary 
of the incident to be used internally to deter malfeasance and promote better community relations.    

## Why Equitable Surveillance?
Social Justice: Automatically enact equity in traditionally inequitable situations.

- Review of dashcam/bodycam videos are not done unless a complaint happens
- Internal review of police dashcam/bodycam videos can improve policing and save lives
- Major intent for dashcam/bodycam usage is to prevent malfeasance but footage is rarely checked.
    - Low incentive for being on best behavior

## Our Solution and Value Proposition
Solution: Platform which audits interactions within an incident.

### Value Proposition
Get a ROI on dashcam/bodycam investment.

- Speed to market
- Open Architecture
- Extendable

## How it works?
<img width="569" alt="Screen Shot 2022-08-01 at 11 08 05 AM" src="https://user-images.githubusercontent.com/57039578/182180783-f1e9d939-3ea6-4223-9590-6f2335a96bce.png">

## Project Structure
Our project is made up of the below repos for the various services we have built for our platform.    
- **[speech-detection](https://github.com/Equitable-Surveillance/speech-detection):** NLP solutions to take audio input and return offensive/hate speech detected in the videos.
- **licenseplate_detection:**  CV solution to detect license plate and extract text information from the videos.
- **gun_detection:** CV solution for situational gun detection from the videos.
- **web_scraping_images:** Webscraping tool to extract videos of guns to support building situational gun detection model.
