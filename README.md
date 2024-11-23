# Instructions

1. Fork the whole Repository
2. Clone to your local Machine
3. In the base folder run ```npm install```

        NB: Hiyo package.json unaona hapa kwa Base folder ni ya backend. Nimetumia hiyo structure sababu ikifika time ya kuhost itakuwa easier that way. From personal experience though. But I think ni approach poa sababu pia nimeona other Devs wakifanya hivyo

4. Start the server by typing: ```npm run dev```

        NB: Hii itarun the Server by navigating to the backend folder and running nodemon app.js. 
    
        Kwa package.json ndio nimeset hivyo if you want to check out

5. Open ```index.js``` in the browser and navigate to the form to try it out.

Setting za database sijachange kitu so you'll use the same things you had

And then utanotice kuna ```.gitignore``` file tena. Hii ni ya kuspecify vitu hutaki kutrack na Git which should always include:

    1. node_modules //Project dependencies
    2. .env //Environment variables



And then hiyo ```.env``` file unaona hapo ni ya credentials zako za database pamoja na the port ya server. 

So any other time ukona credential za kutumika anywhere zieke kwa ```.env```

For Security purposes hivyo ndio unafaa kufanya alafu sasa unaignore kwa ```.gitignore``` ndio usiziweke GitHub

Nimeeka hapo for now sababu ya wewe kuclone but after umeclone uncomment hiyo comment ya ```.env```


Nimeignore ```database.sql``` file yako but utacopy tu yenye ulikuwa nayo sababu sijachange anything

And then pia kuwa unasave ```nodemon``` na ```cors``` as Development dependencies by running the command ```npm install --save-dev <package>``` ama pia ```npm install -D <package>```