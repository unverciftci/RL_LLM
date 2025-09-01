A demo combining LLMs (AI that understands/generates text, like ChatGPT) with reinforcement learning (how AI learns through trial and error, like teaching a dog with treats).

Usually RL uses simple neural networks that just output numbers. But what if we use an LLM as the brain instead?

My demo: a small language model (Qwen3-0.6B) learns to solve mazes by trying moves, hitting walls (-0.5 points), and remembering what failed. After 20 attempts, it's navigating like a pro to the goal (+10 points).

No fine-tuning needed - it literally just remembers past attempts in its prompt: "Last time at position (0,0), going North hit a wall. Let me try East instead."

Like teaching a kid a game without explaining rules - they figure it out by playing and remembering what worked.

Run on Google [Colab:](https://github.com/unverciftci/RL_LLM/blob/main/RL_LLM.ipynb)


