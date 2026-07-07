# Quran Word Game

A free vocabulary game that teaches the most frequent words of the Quran, based on the classic 20-lesson "Quranic Lessons" course. Because the Quran's words repeat so often, finishing all 20 lessons means you will recognise roughly half of all the words in the Quran.

## How it works

Each lesson runs through seven stages:

1. **Learn** - flip-cards for the lesson's new words, with how often each appears in the Quran
2. **Match** - pair the Arabic words with their meanings
3. **Quiz** - multiple choice in both directions
4. **Read** - read a real ayah and guess its meaning
5. **Fill** - complete the ayah's missing word, with its surah and verse reference
6. **Build** - arrange scrambled words to form the ayah
7. **Boss Round** - timed questions that bring back words from earlier lessons

Points are counted as **thawab**, with streak multipliers, star ratings per lesson, and a crescent lit for every 500 thawab. A coverage bar shows what share of the Quran's ~77,000 words you now recognise. Daily Revision retests the words you get wrong most often, and learners who already know the material can test out of earlier lessons.

Lessons 6, 13, 15, 17 and 19 also teach the course's five "Keys of Understanding the Quran" - grammar patterns that each unlock hundreds of words at once.

## Running it

It is a single `index.html` file with no build step and no backend. Open it in any browser, or serve it from any static host. Progress is saved in the player's own browser (localStorage); nothing is collected or transmitted.

## Credits

Word lists, lesson structure, and the five Keys are from the "Quranic Lessons 1-20" course books. All ayat are quoted from the Quran with surah:verse references shown in-game.
