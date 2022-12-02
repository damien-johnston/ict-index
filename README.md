# ICT-Index
## Keyword Search for Transcribed ICT Video Content

### Github Search Syntax Reference
- Official Docs
    - https://docs.github.com/en/search-github/getting-started-with-searching-on-github/about-searching-on-github

- Cheat Sheet Gist
    - https://gist.github.com/bonniss/4f0de4f599708c5268134225dda003e0

### Notes
- The file naming convention is videoId_transcription.json
- The video id can be used for reference if needed.
- There is a 1:1 relationship between video and transcription file.
- File Naming Convention (yyyy-MM-dd-hhmmss-videoId-transcription.json) 
    - i.e. 2022-09-10-070004-FgacYSN9QEo-transcription.json
    - This naming convention shows the date and time of publication by ICT.
    - When searching for terms note the file name to understand when the term has been used.
 
 ### Known Issues
 - Copy and Paste into Github's Search Bar returns no results except for ReadMe file matches.
    - i.e. If a search term is copied and pasted into the search bar, the results are not valid.
    - When the same term is typed into the search bar the results are returned as expected. (No idea why this is the case)

### Use Case
- Keyword Search
- Use Github's Search and Limit Search Scope to This Repo

    ![Keyword Search](./readme-resources/KeywordSearchExample.jpg) 

- Search for Keywords with Github's search syntax.
- "Fair Value Gap" will find the full term (Fair Value Gap)
- Fair Value Gap will find all files with Fair OR Value OR Gap

- Search results provide a generated url with a time offset, to the point when the term is used in the video.

    ![SearchResults](./readme-resources/SearchResults.jpg) 
    
- Select the URL of interest from the search results
    - `https://www.youtube.com/watch?v=FgacYSN9QEo&t=33`
    
    ![SelectURL](./readme-resources/CopyVideoURL.jpg)

- Review the content of interest
    
    ![SelectURL](./readme-resources/ReferenceVideoOffset.jpg)
<<<<<<< HEAD

### Glossary of Terms

| Abbreviation     |     Definition |
| -------------    |     ------------- |
| 𝙰𝙳𝚁    |     𝙰v𝚎𝚛𝚊𝚐𝚎 𝙳𝚊𝚒𝚕𝚢 𝚁𝚊𝚗𝚐𝚎 |   
| 𝙰𝙼𝙳    |     𝙰𝚌𝚌𝚞𝚖𝚞𝚕𝚊𝚝𝚒𝚘𝚗 𝙼𝚊𝚗𝚒𝚙𝚞𝚕𝚊𝚝𝚒𝚘𝚗 𝙳𝚒𝚜𝚝𝚛𝚒𝚋𝚞𝚝𝚒𝚘𝚗   |
| 𝙰𝚃𝚁    |     𝙰v𝚎𝚛𝚊𝚐𝚎 𝚃𝚛𝚞𝚎 𝚁𝚊𝚗𝚐𝚎   |
| 𝙱𝙱     |     𝙱𝚛𝚎𝚊𝚔𝚎𝚛 𝙱𝚕𝚘𝚌𝚔   |
| 𝙱𝙸𝚂𝙸   |     𝙱𝚞𝚢𝚜𝚒𝚍𝚎 𝙸𝚖𝚋𝚊𝚕𝚊𝚗𝚌𝚎 𝚂𝚎𝚕𝚕𝚜𝚒𝚍𝚎 𝙸𝚗𝚎𝚏𝚏𝚒𝚌𝚒𝚎𝚗𝚌𝚢 (𝚋𝚞𝚕𝚕𝚒𝚜𝚑 𝙵V𝙶)   |
| 𝙱𝙼𝚂    |     𝙱𝚛𝚎𝚊𝚔 𝚒𝚗 𝙼𝚊𝚛𝚔𝚎𝚝 𝚂𝚝𝚛𝚞𝚌𝚝𝚞𝚛𝚎   |
| 𝙱𝚂𝙻    |     𝙱𝚞𝚢 𝚂𝚒𝚍𝚎 𝙻𝚒𝚚𝚞𝚒𝚍𝚒𝚝𝚢   |
| 𝙲𝙱𝙳𝚁   |     𝙲𝚎𝚗𝚝𝚛𝚊𝚕 𝙱𝚊𝚗𝚔 𝙳𝚎𝚊𝚕𝚎𝚛 𝚁𝚊𝚗𝚐𝚎   |
| 𝙲𝙴     |     𝙲𝚘𝚗𝚜𝚎𝚚𝚞𝚎𝚗𝚝 𝙴𝚗𝚌𝚛𝚘𝚊𝚌𝚑𝚖𝚎𝚗𝚝 (𝟻𝟶% 𝚘𝚏 𝚊 𝙵V𝙶)   |
| 𝙲𝙾𝚃    |     𝙲𝚘𝚖𝚖𝚒𝚝𝚖𝚎𝚗𝚝 𝚘𝚏 𝚃𝚛𝚊𝚍𝚎𝚛𝚜 (𝚛𝚎𝚙𝚘𝚛𝚝)   |
| 𝙲𝙼𝙴    |     𝙲𝚑𝚒𝚌𝚊𝚐𝚘 𝙼𝚎𝚛𝚌𝚊𝚗𝚝𝚒𝚕𝚎 𝙴𝚡𝚌𝚑𝚊𝚗𝚐𝚎 (𝙱𝚘𝚗𝚍 𝙼𝚊𝚛𝚔𝚎𝚝 𝙾𝚙𝚎𝚗)   |
| 𝙴𝚀𝙷    |     𝙴𝚚𝚞𝚊𝚕 𝙷𝚒𝚐𝚑   |
| 𝙴𝚀𝙻    |     𝙴𝚚𝚞𝚊𝚕 𝙻𝚘𝚠   |
| 𝙵V𝙶    |     𝙵𝚊𝚒𝚛 V𝚊𝚕𝚞𝚎 𝙶𝚊𝚙 (𝚒𝚖𝚋𝚊𝚕𝚊𝚗𝚌𝚎)   |
| 𝙷𝚁𝙻𝚁   |     𝙷𝚒𝚐𝚑 𝚁𝚎𝚜𝚒𝚜𝚝𝚊𝚗𝚌𝚎 𝙻𝚒𝚚𝚞𝚒𝚍𝚒𝚝𝚢 𝚁𝚞𝚗   |
| 𝙷𝚃𝙵    |     𝙷𝚒𝚐𝚑𝚎𝚛 𝚃𝚒𝚖𝚎𝚏𝚛𝚊𝚖𝚎   |
| 𝙸𝙾𝙵    |     𝙸𝚗𝚜𝚝𝚒𝚝𝚞𝚝𝚒𝚘𝚗𝚊𝚕 𝙾𝚛𝚍𝚎𝚛 𝙵𝚕𝚘𝚠   |
| 𝙸𝙾𝙵𝙴𝙳  |     𝙸𝚗𝚜𝚝𝚒𝚝𝚞𝚝𝚒𝚘𝚗𝚊𝚕 𝙾𝚛𝚍𝚎𝚛 𝙵𝚕𝚘𝚠 𝙴𝚗𝚝𝚛𝚢 𝙳𝚛𝚒𝚕𝚕   |
| 𝙸𝙿𝙳𝙰   |     𝙸𝚗𝚝𝚎𝚛𝚋𝚊𝚗𝚔 𝙿𝚛𝚒𝚌𝚎 𝙳𝚎𝚕𝚒v𝚎𝚛𝚢 𝙰𝚕𝚐𝚘𝚛𝚒𝚝𝚑𝚖   |
| 𝙻𝙿     |     𝙻𝚒𝚚𝚞𝚒𝚍𝚒𝚝𝚢 𝙿𝚘𝚘𝚕   |
| 𝙻V𝙶    |     𝙻𝚒𝚚𝚞𝚒𝚍𝚒𝚝𝚢 V𝚘𝚒𝚍 𝙶𝚊𝚙   |
| 𝙻𝚃𝙵    |     𝙻𝚘𝚠𝚎𝚛 𝚃𝚒𝚖𝚎𝚏𝚛𝚊𝚖𝚎   |

| 𝙻𝚁𝙻𝚁   |     𝙻𝚘𝚠 𝚁𝚎𝚜𝚒𝚜𝚝𝚊𝚗𝚌𝚎 𝙻𝚒𝚚𝚞𝚒𝚍𝚒𝚝𝚢 𝚁𝚞𝚗   |
| 𝙼𝙱     |     𝙼𝚒𝚝𝚒𝚐𝚊𝚝𝚒𝚘𝚗 𝙱𝚕𝚘𝚌𝚔   |
| 𝙼𝙼𝙱𝙼   |     𝙼𝚊𝚛𝚔𝚎𝚝 𝙼𝚊𝚔𝚎𝚛 𝙱𝚞𝚢 𝙼𝚘𝚍𝚎𝚕   |
| 𝙼𝙼𝚂𝙼   |     𝙼𝚊𝚛𝚔𝚎𝚝 𝙼𝚊𝚔𝚎𝚛 𝚂𝚎𝚕𝚕 𝙼𝚘𝚍𝚎𝚕   |
| 𝙼𝚃𝙷    |     𝙼𝚎𝚊𝚗 𝚃𝚑𝚛𝚎𝚜𝚑𝚘𝚕𝚍 (𝟻𝟶% 𝚏𝚛𝚘𝚖 𝙾𝙱)   |
| 𝙽𝙵𝙿    |     𝙽𝚘𝚗-𝙵𝚊𝚛𝚖 𝙿𝚊𝚢𝚛𝚘𝚕𝚕   |
| 𝙾𝙱     |     𝙾𝚛𝚍𝚎𝚛 𝙱𝚕𝚘𝚌𝚔   |
| 𝙾𝙷𝙻𝙲   |     𝙾𝚙𝚎𝚗 𝙷𝚒𝚐𝚑 𝙻𝚘𝚠 𝙲𝚕𝚘𝚜𝚎   |
| 𝙾𝚂𝙾𝙺   |     𝙾𝚗𝚎 𝚂𝚑𝚘𝚝 𝙾𝚗𝚎 𝙺𝚒𝚕𝚕   |
| 𝙾𝚃𝙴    |     𝙾𝚙𝚝𝚒𝚖𝚊𝚕 𝚃𝚛𝚊𝚍𝚎 𝙴𝚗𝚝𝚛𝚢   |
| 𝙿𝙰     |     𝙿𝚛𝚒𝚌𝚎 𝙰𝚌𝚝𝚒𝚘𝚗   |
| 𝙿𝙱     |     𝙿𝚛𝚘𝚙𝚞𝚕𝚜𝚒𝚘𝚗 𝙱𝚕𝚘𝚌𝚔 (𝙾𝙱 𝚒𝚗 𝚊 𝙾𝙱)    |
| 𝙿𝙾𝟹    |     𝙿𝚘𝚠𝚎𝚛 𝙾𝚏 𝟹    |
| 𝙿𝙳𝙷    |     𝙿𝚛𝚎v𝚒𝚘𝚞𝚜 𝙳𝚊𝚢 𝙷𝚒𝚐𝚑    |
| 𝙿𝙳𝙻    |     𝙿𝚛𝚎v𝚒𝚘𝚞𝚜 𝙳𝚊𝚢 𝙻𝚘𝚠    |
| 𝙿𝚆𝙷    |     𝙿𝚛𝚎v𝚒𝚘𝚞𝚜 𝚆𝚎𝚎𝚔 𝙷𝚒𝚐𝚑    |
| 𝙿𝚆𝙻    |     𝙿𝚛𝚎v𝚒𝚘𝚞𝚜 𝚆𝚎𝚎𝚔 𝙻𝚘𝚠    |
| 𝚁𝙽     |     𝚁𝚘𝚞𝚗𝚍 𝙽𝚞𝚖𝚋𝚎𝚛𝚜    |
| 𝚁𝙹     |     𝚁𝚎𝚓𝚎𝚌𝚝𝚒𝚘𝚗 𝙱𝚕𝚘𝚌𝚔    |
| 𝚁𝚃𝙾    |     𝚁𝚎𝚝𝚞𝚛𝚗 𝚝𝚘 𝙾𝚛𝚍𝚎𝚛 𝙱𝚕𝚘𝚌𝚔 𝚘𝚛 𝙾𝚛𝚒𝚐𝚒𝚗    |
| 𝚂𝙷     |     𝚂𝚝𝚘𝚙 𝙷𝚞𝚗𝚝    |
| 𝚂𝙸𝙱𝙸   |     𝚂𝚎𝚕𝚕𝚜𝚒𝚍𝚎 𝙸𝚖𝚋𝚊𝚕𝚊𝚗𝚌𝚎 𝙱𝚞𝚢𝚜𝚒𝚍𝚎 𝙸𝚗𝚎𝚏𝚏𝚒𝚌𝚒𝚎𝚗𝚌𝚢 (𝚋𝚎𝚊𝚛𝚒𝚜𝚑 𝙵V𝙶)    |
| 𝚂𝙼𝚁    |     𝚂𝚖𝚊𝚛𝚝 𝙼𝚘𝚗𝚎𝚢 𝚁𝚎v𝚎𝚛𝚜𝚊𝚕    |
| 𝚂𝙼𝚂    |     𝚂𝚑𝚒𝚏𝚝 𝚒𝚗 𝙼𝚊𝚛𝚔𝚎𝚝 𝚂𝚝𝚛𝚞𝚌𝚝𝚞𝚛𝚎     |
| 𝚂𝙼𝚃    |     𝚂𝚖𝚊𝚛𝚝 𝙼𝚘𝚗𝚎𝚢 𝚃𝚎𝚌𝚑𝚗𝚒𝚚𝚞𝚎 (𝚃𝚘𝚘𝚕)     |
| 𝚂𝚂𝙻    |     𝚂𝚎𝚕𝚕 𝚂𝚒𝚍𝚎 𝙻𝚒𝚚𝚞𝚒𝚍𝚒𝚝𝚢    |
| 𝚃𝚂     |     𝚃𝚞𝚛𝚝𝚕𝚎 𝚂𝚘𝚞𝚙     |

=======
>>>>>>> df73b09512f6e6dd9d3399bfd90b9ca46f143f43
