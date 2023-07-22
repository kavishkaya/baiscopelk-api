# This Is Public Api For search and download sinhala subtitle using www.baiscope.lk ... Any One Can Use This Npm Packege..

> Install ✏
```sh
$ npm i baiscopelk-api
```

> Usage ✏

# Search >>>
```js
//Input

const { baiscopelksearch } = require("baiscopelk-api");

const name = "Bird box"

async function searchsub(Moviename) {;
  const results = await baiscopelksearch(Moviename);
  console.log(results);
}

searchsub(name)



// Output
{
  results: [
    {
      index: 1,
      title: 'Bird Box: Barcelona (2023) Sinhala Subtitles | ලොවක නෙත් වැසු අද්භූත සත්වයාගේ තවත් කතාවක්  [සිංහල උපසිරසි] 18+',
      url: 'https://www.baiscope.lk/bird-box-barcelona-2023-sinhala-subtitles/'
    },
    {
      index: 2,
      title: 'Bird Box (2018) Sinhala Subtitles | ලොවක දෙනෙත් වසා දැමූ අස්වාභාවික සත්වයා…!! [සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/bird-box-2018-sinhala-subtitles/'
    },
    {
      index: 3,
      title: 'Birds of Prey: And the Fantabulous Emancipation of One Harley Quinn (2020) Sinhala Subtitles | ජෝකර් ළඟ නැති කොට [සිංහල උපසිරසි සමඟ]',
      url: 'https://www.baiscope.lk/birds-of-prey-and-the-fantabulous-emancipation-of-one-harley-quinn-2020-sinhala-subtitles/'
    },
    {
      index: 4,
      title: 'Earthquake Bird (2019) Sinhala Subtitle | මරණය රැගෙන යන තැනැන්තිය… [සිංහල උපසිරැසි සමඟ] 18+',
      url: 'https://www.baiscope.lk/earthquake-bird-2019-sinhala-subtitle/'
    },
    {
      index: 5,
      title: 'Tito and the Birds (2018) AKA Tito e os Pássaros Sinhala Subtitles | භීතියෙන් වෙලාගත් ටිටෝගේ ලෝකය [සිංහල උපසිරසි සමඟ]',
      url: 'https://www.baiscope.lk/tito-and-the-birds-2018-aka-tito-e-os-passaros-sinhala-subtitles/'
    },
    {
      index: 6,
      title: 'The Angry Birds Movie 2 (2019) Sinhala Subtitles | ඌරු කුරුලු විරසක පසෙකට [සිංහල උපසිරසි සමඟ]',
      url: 'https://www.baiscope.lk/the-angry-birds-movie-2-2019-sinhala-subtitles/'
    },
    {
      index: 7,
      title: 'Birds of Passage (2018) AKA Pájaros de verano Sinhala Subtitles | ලොවට කියනු මැන විහඟුනි….  [සිංහල උපසිරසි සමඟ]',
      url: 'https://www.baiscope.lk/birds-of-passage-2018-aka-pajaros-de-verano-sinhala-subtitles/'
    },
    {
      index: 8,
      title: 'The Yellow Birds (2017) Sinhala Subtitle | යුධ බිමේ කඳුලු කතාව!.. [චිත්‍රපටය සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/the-yellow-birds-2017-sinhala-subtitle/'
    },
    {
      index: 9,
      title: 'Lady Bird (2017) Sinhala Subtitles | අම්මගෙයි දුවගෙයි කතාව…. [සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/lady-bird-2017-sinhala-subtitles/'
    },
    {
      index: 10,
      title: 'To Kill a Mockingbird (1962) with Sinhala Subtitles | “සමානාත්මතාව උදෙසා….” [සිංහල උපසිරසි සමඟ]',
      url: 'https://www.baiscope.lk/to-kill-a-mockingbird-1962-with-sinhala-subtitles/'
    },
    {
      index: 11,
      title: 'Angry Birds (2016) with Sinhala Subtitles |  බිත්තර බේරා ගැනීමේ මහා සටන  [සිංහල උපසිරසි සමඟ]',
      url: 'https://www.baiscope.lk/angry-birds-2016-with-sinhala-subtitles/'
    },
    {
      index: 12,
      title: 'Yellowbird (2014)  |  කහ කුරුල්ලා. [සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/yellowbird-aka-gus-petit-oiseau-grand-voyage-2014-with-sinhala-sub/'
    },
    {
      index: 13,
      title: 'Birdman (2014) | කුරුළු මිනිසා…. [සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/birdman-2014-with-sinhala-sub/'
    },
    {
      index: 14,
      title: 'White Bird in a Blizzard (2014) | අවුලක පැටලුන කිරිල්ලියක්..(100) (18+) [සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/white-bird-in-a-blizzard-2014-sinhala-sub/'
    },
    {
      index: 15,
      title: 'Game of Thrones [S4E07 – Mockingbird]  (18+)| පරණ තරහවල්. [සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/game-of-thrones-s4e07-mockingbird-with-sinhala-sub/'
    },
    {
      index: 16,
      title: 'Free Birds (2013) Sinhala Subtitles | නිදහස් කුරුල්ලෝ… [සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/free-birds-2013-sinhala-subtitles/'
    },
    {
      index: 17,
      title: 'Some Bird Can’t Fly (1997) AKA Ptice koje ne polete Sinhala Subtitle | සමහර කුරුල්ලන්ට පියාඹන්නට නොහැකිය.. [සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/some-bird-cant-fly-1997-aka-ptice-koje-ne-polete-sinhala-subtitle/'
    },
    {
      index: 18,
      title: 'The Lost City (2022) Sinhala Subtitles | අග්නි කිරුළ සොයා බිහිසුණු වික්‍රමයක [සිංහල උපසිරසි]',
      url: 'https://www.baiscope.lk/the-lost-city-2022-sinhala-subtitles/'
    },
    {
      index: 19,
      title: 'The Unforgivable (2021) Sinhala Subtitles | වැරැද්ද කාගෙද? [සිංහල උපසිරසි] 18+',
      url: 'https://www.baiscope.lk/the-unforgivable-2021-sinhala-subtitles/'
    },
    {
      index: 20,
      title: 'The Goldfinch (2019) Sinhala Subtitles | මව් සෙනෙහස අහිමිවී ගිය පුතෙකුට අත්වූ ඉරණම. [සිංහල උපසිරැසි සමඟ]',
      url: 'https://www.baiscope.lk/the-goldfinch-2019-sinhala-subtitles/'
    }
  ]
}
```



# Downloading >>>

```js
const { baiscopelkdownload } = require("baiscopelk-api");

const url = "https://www.baiscope.lk/bird-box-2018-sinhala-subtitles/"

async function downloadsub(Movieurl) {;
  const results = await baiscopelkdownload(Movieurl);
  console.log(results);
}

downloadsub(url)

//Output

{
  title: 'Bird Box (2018) Sinhala Subtitles | ලොවක දෙනෙත් වසා දැමූ අස්වාභාවික සත්වයා…!! [සිංහල උපසිරැසි සමඟ]',
  image: 'https://www.baiscope.lk/wp-content/uploads/2018/12/received_2123665581279996.jpeg',
  DOWN_URL: 'https://www.baiscope.lk/Downloads/bird-box-2018/?tmstv=1690020383'
}

```
