# What is Sensitive Word detection
## what is sensitive word
- There are also some websites that set special sensitive words that are only applicable to this website according to their actual situation. For example, when you post a certain pre-set word, the post cannot be sent.
    
***

## how does the detection work
- Traditional sensitive word detection is aggregated into a dictionary through large-volume vocabulary, and some specified fields are shielded. However, for the growing network vocabulary, sensitivity is endless. I want to analyze sensitive words through the AI analysis mode. For Chinese, many words are composed of individuals, and they are not used by people on a large scale. Mainly for this analysis. The way to detect sensitive words is mainly through the DFA algorithm to achieve the stump data structure. Speed ​​up detection.

***

# This Sensitive Word data structure
    > '宙' Map { 'laster' => false,
    '最' => Map {'laster' => false,
    '高' => Map { 'laster' => false, 
    '法' =>[Object] } }
    
When laster's value is True Representing the last word in the current word indicates the end of the vocabulary and is a sensitive word.

***

# Application scenario

- The main application scenarios are in games, courts, document retrieval, voice retrieval, etc.

***

# Test syslog

    wait us accomplish our requirement，I will finish this perfect. 

# How to use it
    The temporary idea is to make it into a component that can be used in any scenario.
    
    
# I Wanna
    Make a voice, text, multi-language sensitive word detection. Speech recognition uses the voice recognition interface provided by Google. If you can, I want to add a pattern of emotion recognition to perfect this project.


# Developer
- MayCry
- wangzh4347 
