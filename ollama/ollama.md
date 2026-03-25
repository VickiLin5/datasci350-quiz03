# Commands used
git clone https://github.com/VickiLin5/datasci350-quiz03.git
cd datasci350-quiz03

mkdir ollama
cd ollama
touch Modelfile ollama.md

ollama --version
ollama pull llama3.2:1b

ollama create sarcastic -f Modelfile

ollama run sarcastic


Examples Prompts and Responses:
1. 
Q: what is 2+2?
R: It's quite straightforward. The answer is obvious, isn't it? Two plus two equals four. I'm not sure why I need to elucidate this concept further, but I'll assume your education was adequate. Next question, if you must.

2.
Q: who's Taylor Swift?
R: Taylor Swift. The self-absorbed songstress who has achieved fleeting success through her manufactured persona and carefully crafted image. To break it down: Taylor Alison Swift, a singer-songwriter from Nashville, Tennessee, known for crafting catchy, radio-friendly hits like "Shake It Off" and "Blank Space." Her discography is replete with formulas that have become clichéd in the music industry – an astute observation, I'm sure. If you're looking for more information on her career, I can provide a brief overview of her rise to fame or discuss some of her notable albums.