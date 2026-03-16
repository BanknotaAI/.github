# BanknotaAI
### *Tools for the people who document everything the internet is trying to forget.*

---

We didn't build these tools for the market.

We built them because someone has to.

Every subculture, every underground scene, every community that existed before the algorithm decided what mattered — they left traces. Flyers photocopied in back rooms. Zines passed hand to hand. Images uploaded to forums that no longer exist. Events that happened and meant everything to the people who were there, and nothing to the platforms that were supposed to preserve them.

That memory is disappearing. Not dramatically. Not all at once. Just quietly, one dead link at a time.

BanknotaAI is a set of open source tools for finding that memory, saving it, organizing it, and making it trainable — so communities can build AI systems that reflect their own culture instead of whatever the mainstream decided was worth keeping.

The tools are free. They always will be. That's not a business decision. That's a principle.

---

## What We Built

### RubySpiderWeb
An infinite-depth web crawler that finds images, decodes them with OCR, and cross-references them against music and cultural databases. Built for archivists. Works for anyone.

`find → crawl → decode → enrich → archive`

### Delphos Snake
A professional dataset curation tool for people building AI training pipelines. Review, tag, score, export. Full Tier 1–3 feature set. No subscription required.

`load → curate → tag → quality-check → export to Kohya_ss`

### Seductress
A wide-net search engine for finding sources that mainstream search doesn't surface. Because the good stuff is never on page one.

`search → harvest → pipeline`

---

## The Pipeline

These three tools are not separate applications. They are one system.

```
Seductress          →    RubySpiderWeb       →    Delphos Snake       →    Kohya_ss / LoRA
─────────────────        ─────────────────        ─────────────────        ─────────────────
Find sources             Crawl + archive           Curate + caption         Train your model
Discover archives        OCR + enrich              Quality score
Surface the buried       Deduplicate               Export training set
```

End to end. Yours to run, modify, fork, and keep.

---

## Who This Is For

- The archivist who has been saving rave flyers since 1993 and doesn't know what to do with 40,000 images.
- The researcher documenting protest movements before the footage gets taken down.
- The diaspora community that wants an AI that actually knows their culture.
- The independent artist building a model trained on their own work, not someone else's.
- The journalist archiving sources before platforms delete them.
- The underground scene that never had a Wikipedia page and never will.
- The developer who needs a crawler and doesn't want to pay enterprise prices for something they could run themselves.

If you've ever felt like the internet was eating history and nobody was doing anything about it — this is for you.

---

## On Money

We're not a startup. We're not looking for Series A. We're not pivoting to enterprise.

If you use these tools and want to support the work, there will be ways to do that. If you're an institution or organization that needs hosted versions or support, we can talk. If you're a foundation that funds digital preservation, we'd love to hear from you.

But the tools stay free. That's the deal.

---

## On AI

We believe communities should own the AI systems that represent them. The way that happens is through data sovereignty — having control over what goes into a model, how it's curated, and what it learns.

Delphos Snake exists because that pipeline was broken and nobody had fixed it.

We're not anti-AI. We're anti-AI-that-erases-you.

---

## A Note From the Person Who Built This

For years I carried ideas I couldn't execute. I had the vision and no tools to match it.

I grew up with stencils and spray cans, carbon paper and cardboard, making art from whatever I could find. I spent years in human rights work, helping communities document their realities and fight for their stories to be heard. I had an academic foundation in social sciences and was around early machine learning research when it was still happening in dim-lit university offices — before it became an industry. I understood what these tools could do for people long before most people were paying attention.

But I couldn't build. Not yet.

When AI-assisted development became real — when the average person could sit down and turn a vision into working software — I felt something shift. This was the moment I had been waiting for without knowing I was waiting for it.

I'll be honest: part of me just wanted to be Acid Burn from Hackers 1995. That movie is technically ridiculous and spiritually correct in equal measure. It got everything wrong about how computers work and everything right about why some of us are drawn to them — the idea that these machines were tools for the curious, the weird, the people who saw systems differently. The rollerblades were fake. The ethos wasn't.

So I built what I always needed. Tools for finding the underground. Tools for saving what the internet is quietly deleting. Tools for turning a lifetime of collected images, influences, and cultural memory into something trainable, usable, and yours.

I'm not a programmer. I'm someone who finally got the blade sharp enough to cut the stencil I designed twenty years ago.

This is for the kid with the crusty magazine and the carbon paper. This is for every community that documented itself before anyone was watching. This is for everyone who ever felt like the tools weren't built for them.

They are now.

*— Guillermo, BanknotaAI*

---

## Repositories

| Tool | Description | Status |
|------|-------------|--------|
| [RubySpiderWeb](https://github.com/BanknotaAI/RubySpiderWeb) | Web crawler + cultural archive engine | Active |
| [DelphosSnake](https://github.com/BanknotaAI/DelphosSnake) | Dataset curator + Kohya_ss exporter | Active |
| [Seductress](https://github.com/BanknotaAI/Seductress) | Wide-net search engine | Active |
| [SupremeGrind](https://github.com/BanknotaAI/SupremeGrind) | Banknota universe game | In development |

---

## Getting Started

Each tool runs locally on Windows, Mac, or Linux. Python 3.12+ required.

```bash
# RubySpiderWeb
git clone https://github.com/BanknotaAI/RubySpiderWeb
cd RubySpiderWeb
py -m pip install -r requirements.txt
py ruby_spider_gui.py

# Delphos Snake
git clone https://github.com/BanknotaAI/DelphosSnake
cd DelphosSnake
py -m pip install -r requirements.txt
py ui_main.py

# Seductress
git clone https://github.com/BanknotaAI/Seductress
cd Seductress
py -m pip install -r requirements.txt
py seductress_gui.py
```

---

## License

MIT. Take it, fork it, build on it. Just don't close it.

---

*BanknotaAI is built by El Gorro and collaborators.*
*The aesthetic is intentional. The principles are non-negotiable. The code is yours.*
