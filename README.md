# Sinhala Addendum Keyboard Layout
This is a custom keyboard layout for the Sinhalese script that aims to be easy to use for anyone with a QWERTY keyboard. 
The main goals of this layout are,
- To provide an layout that would be easy to transition for anyone used to typing *Singlish* (*Not to be Confused with Singlish of Singapore*)
- To be trivial to figure out/use the layout without needing the Sinhala characters printed on keys
- ...and to give myself something as half as decent as [sl-sayura-m17n-db](https://github.com/mike-fabian/m17n-db-sayura) on windows
## Table of Content
- [Layout Preview](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/main/README.md#layout-preview)
- [Layout Details](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/main/README.md#layout-details)
- [Dead Key Tables](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/main/README.md#dead-key-tables)
  - [Dead Key  `ං` (Qwerty Key `x`)](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/main/README.md#dead-key--%E0%B6%82-qwerty-key-x)
  - [Dead Key `ඃ` (Qwerty Key `X`)](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/main/README.md#dead-key-%E0%B6%83-qwerty-key-x)
  - [Dead Key `` ` `` (Backtick/Accent Aigu)](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/main/README.md#dead-key--backtickaccent-aigu)
## Layout Preview
![Screenshot 2024-03-09 144409](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/assets/66691814/92b5067a-f918-43b9-af21-735ce30a9123)
![Screenshot 2024-03-09 144422](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/assets/66691814/0b670219-8f73-48ed-a0e7-96ae3a84a982)
![Screenshot 2024-03-09 144432](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/assets/66691814/73f0c57a-77d2-41b7-926a-466ab86f1295)
![Screenshot 2024-03-09 144442](https://github.com/AdelinaM17n/Sinhala-Addendum-Keyboard-Layout/assets/66691814/937aafff-9363-4c6b-9c68-8b29c5607513)


## Layout Details
- All aspirated consonats can be accessed by pressing `SHIFT` alongside the key corresponding to the non-aspirated consonant, except for four consonants
  - The exceptions are the aspirated versions of `ට, ත, ද, ඩ`. For those letters you instead have to hit `AltGr` (Ctrl+Alt) and the corresponding key to access the aspirated version. (Reasons why will be explained bellow)
  - **ALTERNATIVELY** You can access any aspirated consonant utilising dead keys, Entering `SHIFT+X` and any valid consonant afterwards will allow you to type the aspirated consonant
- Accessing pre-nasalised letters (sannyaka akuru, ardha-anu-nasikya akshara) depends on the letter, Refer to the above layout preview to see where to access each letter
  - **ALTERNATIVELY** You can access any pre-nasalised consonant with dead keys, Entering the `x` key and any valid consonant afterwards will allow you to access its pre-nasalised form
- Refer to the above layout preview for vowel letters, every vowel letter requires the `altGr` key or **alternatively, the use of the dead key** `` ` `` alongside the corresponding vowel marker (For example  `ැ` ->  `ඇ`, Although for අ and ආ pleaase refer to the dead key table) to be inputted
- Ligatures such as `ක්‍ය` (yanshaya) and `ක්‍ර` (rakaraanshaya) can be accessed with `SHIFT+Y` and `SHIFT+R` respectively. For any other godforsaken ancient ligature, Please manually type them. This layout allows you to type a unicode `Zero Width Joiner` with `altGr + shift + ,`. Refer to  [Wikipedia Consonant Conjuncts List](https://si.wikipedia.org/wiki/%E0%B7%83%E0%B7%92%E0%B6%82%E0%B7%84%E0%B6%BD_%E0%B6%85%E0%B6%9A%E0%B7%8A%E0%B7%82%E0%B6%BB_%E0%B6%B8%E0%B7%8F%E0%B6%BD%E0%B7%8F%E0%B7%80#Consonant_conjuncts) to know which letters are needed for the the ligature
- Some keys are repeated in the layout for ease of use and/or preference, or perhaps to attain a fake sense of consistency with some letters
   
~~Layout screenshots are terrible I know, I don't know any better way to preview it~~
## Dead Key Tables

### Dead Key  `ං` (Qwerty Key `x`)
   
| Base Qwerty Key | Base Letter | Resulting Letter |
| --------------- | ----------- | ---------------- |
| g               | ග           | ඟ                |
| j               | ජ           | ඦ                |
| d               | ඩ           | ඬ                |
| D               | ද           | ඳ                |
| b / m           | බ / ම       | ඹ                |

### Dead Key `ඃ` (Qwerty Key `X`)

| Base Qwerty Key | Base Letter | Resulting Letter |
| --------------- | ----------- | ---------------- |
| k               | ක           | ඛ                |
| c               | ච           | ඡ                |
| T               | ට           | ඨ                |
| t               | ත           | ථ                |
| p               | ප           | ඵ                |
| g               | ග           | ඝ                |
| j               | ජ           | ඣ                |
| D               | ඩ           | ඪ                |
| d               | ද           | ධ                |
| b               | බ           | භ                |

### Dead Key `` ` `` (Backtick/Accent Aigu)

| Base Qwerty Key | Base Character | Resulting Letter |
| --------------- | -------------- | ---------------- |
| a               | ා              | අ                |
| A               | ්              | ආ                |
| q               | ැ              | ඇ                |
| Q               | ෑ              | ඈ                |
| i               | ි              | ඉ                |
| I               | ී              | ඊ                |
| u               | ු              | උ                |
| U               | ූ              | ඌ                |
| F               | ෘ              | ඍ                |
| V               | ෲ              | ඎ                |
| altGr + l       | ෟ              | ඏ                |
| altGr + L       | ෳ              | ඐ                |
| e               | ෙ              | එ                |
| E               | ේ              | ඒ                |
| W               | ෛ              | ඓ                |
| o               | ො              | ඔ                |
| O               | ෝ              | ඕ                |
| w               | ෞ              | ඖ                |
