# Litigation-Copilot

## Demo
Demonstrating a preliminary, legal case analysis based on a case text file supplied using a privately deployed LLM. 
(LLM is like ChatGPT)
So, no questions and answers are shared with a service provider like OpenAI or Google.

```python
response = query_engine.query("Wbat is this case about")

```

This case is about a plaintiff, Gipson, who is suing several defendants for alleged violations of the Texas Constitution, the Texas Penal Code, and the Foreign Sovereign Immunity Act of 1976. Gipson claims that the defendants violated his right to due process and other constitutional rights. The defendants have filed a motion to dismiss the case, arguing that they are entitled to absolute or qualified immunity. The court examines the specific assertions and ultimately grants the motion to dismiss, finding that Gipson has failed to allege any specific facts to overcome the judicial or prosecutorial immunity of the defendants.

```python
response = query_engine.query("Wbat was the key winning argument?")

```

The key winning argument was that Gipson failed to provide specific facts to overcome Defendants Kenneth Callahan's and Jake Ussery's qualified immunity. Gipson's factual allegations did not support his claims that the Defendants violated his constitutional rights, and Gipson failed to allege specific facts showing that the Defendants' actions were objectively unreasonable. Furthermore, Gipson's bare allegations were insufficient to overcome Callahan's qualified immunity.

