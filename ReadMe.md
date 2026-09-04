# -- -- 

- git subtree add --prefix=Git.Ext https://github.com/247i/Git.Ext  முதன்மை --squash
- git subtree add --prefix=Git.Ext https://github.com/247i/Git.Ext  முதன்மை --squash
- git submodule add https://github.com/247i/GitHubDesktop

# யாராவது Azhagi ரிப்போசிட்டரியில் மாற்றம் செய்து, அதை நீங்கள் Git.Ext ஃபோல்டரில் புதுப்பிக்க விரும்பினால்:
git subtree pull --prefix=Git.Ext https://github.com/247i/Azhagi.git முதன்மை --squash

# நீங்கள் பிரதான ரிப்போசிட்டரியில் உள்ள Git.Ext ஃபோல்டருக்குள் வேலை செய்து கமிட் செய்த மாற்றங்களை அசல் லிங்கிற்கு அனுப்ப
git subtree push --prefix=Git.Ext https://github.com/247i/Azhagi.git முதன்மை

