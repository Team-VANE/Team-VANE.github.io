+++
date = '2026-10-12T14:40:33+03:00'
draft = false
title = 'How Github Actions helps Sonic VANE.'
author = 'Wingzzzzy'
+++
In this blog post I will be talking about our recent addition of adding github actions to the game and how helpfull it is for packing our unique fan game. Unlike other fan games where you build once and sent this one builds each part of the assets as its own unencrypted pkg file and becouse of that its time consuming to pack every os version we support into it's own zip before i made this Marble the main person on this project made it using just a ziped up executable and the data folder inside a proton drive. It was a pain to extract everything right and making it work. But now with this new automation now we don't have to do anything. But also we made it so it can built on linux without problems. As we don't see it as oh lets make a 2.0 version as the game is gonna be a continusly living game so all versions are based on the date when it was built. But also with the automation we can also quickly release it on the releases page of github and auto build the site to show the latest change logs.