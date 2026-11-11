# Unit 5: Interpreting and Applying AI-Generated Insights

An interactive lecture that runs in a web browser. An AI system gives you a label and a score. In this lecture you do the system's work yourself, try to fool it, set its threshold, audit it with a time limit, and design the human review around it.

**Open the lecture:** https://cynthialmcginnis.github.io/unit-5-ai-insights/

## What you do

1. **Run an earthquake alarm.** You have eight seconds and two sensor readings.
2. **Do a language service's work.** Pick the phrases that matter in a voicemail, compare them with six outputs, and write a note to a supervisor.
3. **Check a GenAI summary.** Find the sentences it invented.
4. **Place eight systems** as Sort, Spot, or Trigger.
5. **Fool a tone scorer.** A working scorer labels what you type.
6. **Read confidence scores.** Ten labels all score near 0.90. Count how many are right.
7. **Test two scoring machines.** One is not reliable. One is not relevant.
8. **Set a threshold in 3D, then build a rule.** See how the threshold changes misses and false alarms across 100 customer messages.
9. **Audit ten travel claims in 75 seconds** with an AI label on every line.
10. **Design a review** with a limited budget and run it for a month. Then match six systems to a human in the loop, on the loop, or out of the loop.

Each task is followed by the reason behind it and what to do about it. The lecture opens with a short page on what to do after cross-validation.

The lecture ends with four questions you answer about your own AI system.

## Real Tools Lab

`real-tools-lab.ipynb` is a Google Colab notebook that goes with the lecture. You run a real sentiment model, read its real confidence scores, try to fool it, test whether it is reliable, and set a threshold on 50 scored messages. You run cells and type into boxes. You do not write code.

**Open it in Colab:** https://colab.research.google.com/github/cynthialmcginnis/unit-5-ai-insights/blob/main/real-tools-lab.ipynb

## What it teaches

- Each output of a language service is one measurement. A person connects them.
- Picking a label and writing new text fail in different ways.
- The setting changes what a label means.
- A confidence score shows how closely an input matches what the model has seen. It does not show that the label is right.
- A score has to be reliable and relevant before anyone acts on it.
- A lower threshold gives fewer misses and more false alarms. A person chooses it.
- People tend to agree with an automated answer. A review process has to be designed against that.

## How to use it

- Use the arrow buttons or the left and right arrow keys to change pages.
- **Agenda** jumps to any section.
- **Pick a student** shows one name from the class list at random. No name repeats until every name has been picked.
- **Class list** changes the names. The list saves in your browser.
- The last page has a button that prints the whole lecture with your work, or saves it as a PDF.

Everything you type stays in your own browser. The page sends nothing anywhere.

## Running it

The lecture is one file, `index.html`. There is nothing to install.

- Open the link above, or
- Download `index.html` and open it in any browser.

The two 3D views load the three.js library from the internet. Without a connection, the rest of the lecture still works, including the sliders and counts on the 3D pages.

## Notes

- Setouchi Net, the supply office note, the travel claims, and all scores are made up for teaching.
- The real cases are the Japan Earthquake Early Warning false alarm of January 5, 2018, the New York City business chatbot tested by The Markup in 2024, the flight simulator study by Skitka, Mosier, and Burdick (1999), and the 2003 Patriot incidents reviewed by the Defense Science Board.

## Author

Cynthia McGinnis

## License

MIT License. See `LICENSE`.
