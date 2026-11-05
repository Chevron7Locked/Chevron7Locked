# Kevin O'Neill

My dad got me a reel-to-reel recorder when I was first learning drums, and I've been recording ever since. I worked in studios before I got into software: SoundScape Studios in Chicago with Mike Kolar, then an internship with Joey Sturgis at Foundation in Michigan on Crown the Empire's *The Fallout*, tracked with my Lauten Audio Oceanus. I played shows and short tours, and recorded myself and a lot of local artists.

I took C++ at Elgin Community College through most of the second year and taught myself after that. My first site was sassykatrecords.com in 2012, for my own studio. I've been a professional developer since 2016 and I've run engineering teams since 2020, up to 15 developers at a time.

In the past year and a half I've built an audio matching engine, a native iOS app and post-quantum encrypted messaging by running AI agents the way I run my teams. The models run on five machines of my own, and the agents work from a private library of over 500 books and papers.

### Projects

[Kima](https://github.com/Chevron7Locked/kima-hub) is an open-source music server you run at home, with over 1,290 stars. Play a song, ask for more like it, and it looks for tracks that feel the same. Each track gets 512 numbers from an audio model called CLAP, two more for how positive and how intense it feels, and the artist's genres from MusicBrainz. In 446 odd-one-out listening tests, matching agreed with people 69.7% of the time. Chance is 33%.

[Kima for iOS](https://github.com/Chevron7Locked/kima-ios) is the native app, in TestFlight with the source public. It draws the map of your library in Metal.

Silta is the messaging server my apps plug into, one Go binary on PostgreSQL and Redis, running at silta.chevron7.io from a private repo. One-to-one messages are end-to-end encrypted with X25519 plus post-quantum ML-KEM-768, so the server only relays ciphertext. OSOL, a private social app for my friends and family based on the old AOL platforms, runs on Silta.

ADAgent, which I built at my last job, is company property, so there's no link. It traces each WCAG violation to its source and fixes it there deterministically, and the model only makes judgment calls like alt text. It ran on about half of our client sites and fixed around 85% of the violations found on each one.

### Open source

I have two pull requests merged in [openclaw](https://github.com/openclaw/openclaw) (about 394k stars). One clears auto-failover overrides so the primary model is retried, and the other includes `.env` variables in the gateway service environment on install. Another is merged in [freelingo](https://github.com/artcc/freelingo), and I have three open in [Hermes Agent](https://github.com/NousResearch/hermes-agent).

---

kevin@chevron7.io · [linkedin.com/in/kevinallen3](https://linkedin.com/in/kevinallen3)
