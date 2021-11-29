# <img src='https://raw.githack.com/FortAwesome/Font-Awesome/master/svgs/solid/question.svg' card_color='#22a7f0' width='50' height='50' style='vertical-align:bottom'/> Wolfram Alpha

## Summary

General knowledge fallback handler based on [Wolfram Alpha](https://wolframalpha.com) services

## Description

Answers general knowledge, math, and definition questions by using Wolfram Alpha Api services. If the user is interested in knowing where the information for the spoken answer came from, Neon can send the most recent source of the spoken details to user’s email.
Responses are cached and saved for later use.

Use of this skill requires use of third-party APIs. If you do not have access to Neon API servers, you may access the
Wolfram|Alpha API directly by providing a key in `~/wolfram.txt`. You can generate a Wolfram|Alpha key
[here](https://developer.wolframalpha.com/portal/myapps/).

## Examples

Ask Neon any questions starting with `What`, `Why`, or `How`
- What is 2 + 2
- Who won best picture in 2006
- How far away is the moon

To receive an email with related information:
- Send me the source for that

> **Please note that Neon will ask for your email address and name if this information is not currently available in your user settings.**

## Details

### Text
        
        How far away is the moon?
        >> The distance from Earth to the Moon at 9:21 P.M. CET, Thursday, February 21, 2019 is about 225332 miles. Provided by WolframAlpha.
        
        Send me the source.      
        >> I've sent you an email with details from Wolfram Alpha.  
        
### Picture

### Video

  

## Troubleshooting

Make sure that your wolfram credentials are active and in the correct format before starting the work with this skill or
if you are experiencing any problems with it.

  

## Contact Support

Use the [link](https://neongecko.com/ContactUs) or [submit an issue on GitHub](https://help.github.com/en/articles/creating-an-issue)

## Credits
[Mycroft AI](https://github.com/MycroftAI)
[NeonDaniel](https://github.com/NeonDaniel)
[reginaneon](https://github.com/reginaneon)

