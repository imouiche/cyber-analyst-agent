# cyber-analyst-agent
- This security analyst agent deployed as SAAS app takes a python code, analyse it to identify associated vulnerabilities.
- It first calls the SEMGREP tool to analyze the python file and then call the OPENAI API agent to review the code again and identify vulnerabilites where not identified by SEMGREP.
- It returns both SEMGREP and its own results in a structured output format.

https://cyber-analyzer-kjmxxgvpha-uc.a.run.app/
