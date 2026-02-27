### redteam-ai-scripts  

https://github.com › threatexpress › red-team-scripts

A collection of Python and Bash scripts that leverage Large Language Models (LLMs) for red team automation.

- Automated OSINT and reconnaissance chaining
- Evasion technique generation (obfuscated payloads, C2 profiles)
- AI-assisted report drafting and vulnerability chaining suggestions

### Included Scripts
- `recon-llm.py`          — LLM-powered subdomain/user/email enumeration
- `evasion-gen.py`        — Generate obfuscated PowerShell/shellcode
- `report-helper.py`      — Summarize findings into clean Markdown reports
- `phish-content-gen.py`  — Realistic phishing email body generator

### Setup
```bash
pip install -r requirements.txt
# Add your API key in .env
OPENAI_API_KEY=sk-...
# Or use local models (Ollama, etc.)

## Example
python recon-llm.py --target "example.com" --model gpt-4o-mini
