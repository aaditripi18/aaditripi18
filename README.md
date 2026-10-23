## Hi, I'm Aaditya Tripathi

Final-year student at **Vellore Institute of Technology (VIT), Vellore**.

I build tools at the intersection of **machine learning and security**, and I check every claim against real data.
Most of my projects start from a question someone usually takes on trust: *Is this model file safe? Is this benchmark score real? Did the server actually forget my data?* Then they measure the answer on public data, with every number traceable to a log.

### Featured work

| Project | What it finds | Try it |
|---|---|---|
| [**SOC APT Attribution**](https://github.com/aaditripi18/soc-apt-attribution-platform) | Names the threat group behind an attack only on evidence specific to that group, and explains every MITRE ATT&CK technique it counts. Tested on 105 unseen public attack recordings with no wrong attribution. | [Live demo](https://soc-apt-attribution.vercel.app) |
| [**Stowaway**](https://github.com/aaditripi18/Stowaway) | Finds data hidden inside AI model files: payloads in the weights, unaccounted bytes, unsafe pickle code. 39 popular models surveyed. | [Live demo](https://stowaway-jade.vercel.app) |
| [**leakcheck**](https://github.com/aaditripi18/leakcheck) | Finds train/test leakage in security ML datasets and measures how much reported accuracy it inflates. 8 benchmarks audited. | [Live demo](https://leakcheck-nu.vercel.app) |
| [**CPES**](https://github.com/aaditripi18/CPES) | Finds which Windows process gained privilege, and how, from Sysmon process trees, with an explained score for every alert. Tested on 53 public attack captures and against 850 SigmaHQ rules. | Local dashboard |
| [**Trustworthy Federated Unlearning**](https://github.com/aaditripi18/Trustworthy-Federated-Unlearning) | Keeps a chest X-ray Vision Transformer's explanations stable when a hospital's data is unlearned from a federated model. Evaluated on NIH ChestX-ray14 with three explainers, radiologist boxes and a membership-inference audit. | Local dashboard |

### Hackathons

- 🥉 **3rd place, AI Hackathon at the India AI Impact Summit 2026**: [Rare-Disease Protein Impact Explorer](https://github.com/aaditripi18/Rare-Disease-Protein-Impact-Explorer) maps AlphaMissense variant risk onto AlphaFold structures and finds 3D mutation hotspots. Team of 4.
- **Caterpillar hackathon 2026**: [Smart Operator Assistant](https://github.com/aaditripi18/caterpillar), an in-cab safety assistant for excavators and loaders with live alerts, 4 ML models and a voice co-pilot. Team of 4.

### What I work with

**ML:** PyTorch · scikit-learn · Vision Transformers · federated learning · machine unlearning · membership-inference attacks · explainability
**Security:** threat detection · MITRE ATT&CK · Sysmon · Sigma rules · model supply-chain security · ML dataset auditing
**Building:** Python · TypeScript · React · FastAPI · Streamlit · Kaggle GPU pipelines · reproducible experiment ledgers

### How I work

- **Real data, not toy examples.** Public attack recordings, public models, public benchmarks.
- **Report what failed too.** Each README says where the method breaks, not only where it works.
- **Reproducible.** Fixed seeds, logged runs, tests, and numbers generated from the results rather than typed by hand.

### Contact

📧 aaditripi@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/aaditya-tripathi-35b7573a4)
