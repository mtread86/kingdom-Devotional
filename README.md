Have you talked to God today?

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Bible Verse</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 5%;
            background: #f3f4f6;
            color: #333;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            display: inline-block;
            max-width: 600px;
        }
        h1 {
            color: #4a90e2;
        }
        .verse {
            font-size: 1.5em;
            margin: 20px 0;
            line-height: 1.8em;
        }
        footer {
            margin-top: 30px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Daily Bible Verse</h1>
    <div class="verse" id="bibleVerse"></div>
</div>

<footer>
    © 2024 - Powered by Kingdom Devotionals
</footer>

<script>
    const verses = [
        "John 3:16 - For God so loved the world, that He gave His only begotten Son.",
        "Philippians 4:13 - I can do all things through Christ who strengthens me.",
        "Psalm 23:1 - The Lord is my shepherd; I shall not want.",
        "Romans 8:28 - And we know that in all things God works for the good of those who love Him.",
        "Proverbs 3:5 - Trust in the Lord with all your heart and lean not on your own understanding.",
        "Isaiah 40:31 - But those who hope in the Lord will renew their strength.",
        "Jeremiah 29:11 - For I know the plans I have for you, declares the Lord.",
        "Matthew 6:33 - But seek first the kingdom of God and His righteousness.",
        "Hebrews 11:1 - Now faith is the substance of things hoped for, the evidence of things not seen.",
        "Psalm 46:1 - God is our refuge and strength, a very present help in trouble.",
        "Matthew 5:16 - Let your light shine before others, that they may see your good deeds and glorify your Father in heaven.",
        "2 Corinthians 5:7 - For we walk by faith, not by sight.",
        "Joshua 1:9 - Be strong and courageous. Do not be afraid; do not be discouraged, for the Lord your God will be with you wherever you go.",
        "Psalm 121:1-2 - I lift up my eyes to the hills—where does my help come from? My help comes from the Lord, the Maker of heaven and earth.",
        "1 Peter 5:7 - Cast all your anxiety on Him because He cares for you.",
        "Proverbs 18:10 - The name of the Lord is a fortified tower; the righteous run to it and are safe.",
        "Isaiah 41:10 - Do not fear, for I am with you; do not be dismayed, for I am your God.",
        "Romans 12:12 - Be joyful in hope, patient in affliction, faithful in prayer.",
        "Matthew 11:28 - Come to Me, all you who are weary and burdened, and I will give you rest.",
        "Philippians 4:6 - Do not be anxious about anything, but in every situation, by prayer and petition, with thanksgiving, present your requests to God.",
        "2 Timothy 1:7 - For God has not given us a spirit of fear, but of power, love, and a sound mind.",
        "Psalm 27:1 - The Lord is my light and my salvation; whom shall I fear?",
        "Ephesians 2:8 - For it is by grace you have been saved, through faith—and this is not from yourselves, it is the gift of God.",
        "Psalm 37:4 - Delight yourself in the Lord, and He will give you the desires of your heart.",
        "James 1:5 - If any of you lacks wisdom, you should ask God, who gives generously to all without finding fault.",
        "Galatians 6:9 - Let us not grow weary in doing good, for at the proper time we will reap a harvest if we do not give up.",
        "Colossians 3:23 - Whatever you do, work at it with all your heart, as working for the Lord, not for men.",
        "1 Corinthians 16:13 - Be on your guard; stand firm in the faith; be courageous; be strong.",
        "Psalm 34:8 - Taste and see that the Lord is good; blessed is the one who takes refuge in Him.",
        "Matthew 28:20 - And surely I am with you always, to the very end of the age.",
        "1 John 4:19 - We love because He first loved us.",
        "Romans 5:8 - But God demonstrates His own love for us in this: While we were still sinners, Christ died for us.",
        "Isaiah 43:2 - When you pass through the waters, I will be with you.",
        "Psalm 91:1 - Whoever dwells in the shelter of the Most High will rest in the shadow of the Almighty.",
        "Micah 6:8 - Act justly, love mercy, and walk humbly with your God.",
        "1 Thessalonians 5:16-18 - Rejoice always, pray continually, give thanks in all circumstances.",
        "John 14:27 - Peace I leave with you; My peace I give you.",
        "Exodus 14:14 - The Lord will fight for you; you need only to be still.",
        "Isaiah 54:17 - No weapon formed against you shall prosper.",
        "Psalm 118:24 - This is the day the Lord has made; let us rejoice and be glad in it.",
        "Lamentations 3:22-23 - His mercies are new every morning.",
        "Matthew 19:26 - With God, all things are possible.",
        "2 Chronicles 7:14 - If My people... will humble themselves and pray, I will heal their land.",
        "Hebrews 13:8 - Jesus Christ is the same yesterday, today, and forever.",
        "Proverbs 16:9 - In their hearts, humans plan their course, but the Lord establishes their steps.",
        "John 8:12 - I am the light of the world. Whoever follows Me will never walk in darkness.",
        "Isaiah 26:3 - You will keep in perfect peace those whose minds are steadfast.",
        "James 4:8 - Come near to God and He will come near to you.",
        "Revelation 21:4 - He will wipe every tear from their eyes. There will be no more death or pain."
    ];

    function getRandomVerse() {
        const randomIndex = Math.floor(Math.random() * verses.length);
        document.getElementById('bibleVerse').innerText = verses[randomIndex];
    }

    window.onload = getRandomVerse;
</script>

</body>
</html>
