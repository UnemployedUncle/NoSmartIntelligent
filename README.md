# NoSmartIntelligent

Transform Youtube into daily English study notes.

## Key Features

- **Premade Notes to Start**: Premade notes which I made during development.
    - [ ] StatQuest
    - [ ] 3Blue1Brown
    - [ ] Deeplearning.ai
    - [ ] TwoMinutePapers
    - [ ] AI Explained
    - [ ] CodeEmporium
    - [ ] IBM Technology
    - [ ] ByteByteGo

- **(TBD) Personalized Study Notes**:
    - Link2Note: AI generate high-quality Markdown content for efficient and effective practice.
        - [ ] Link2transcript
        - [ ] Summarization
        - [ ] rewrite eaily > rewrite base on the level > Question
    - Personal Study Notes: Just check function that you want to includ inside your personal study notes.
        - functions / task / knowhow
            - cehcklist
            - quiz (rewrite contents to question, thinking points)
            - fact/source checker
            - additional readings / study materials(link) / information / reference
    - Knowhow Sharing: Add functions by sharing your own knowhow.

- **(TBD) Automate & Feedback**: Modify and adapt the generated notes to fit your personal learning style. Share it to the community. (share routine ~ how to study, contents-youtube, ai-prompt engineered?)
    - [ ] Output Markdown Template 의미 있는 템플릿 생성(사람들이 자주 쓰는 형태 데이터로 축적)
    - [ ] Versioning 기능, 오답 노트 기능
Data ~ 모델 학습
Agent, mass customization(on the shelf)

- [ ] feedback loop

- [ ] Front
고객 관점부터 시작(How to use eaily?, 기술은 숨어 있으야함)
Page 1. 매일매일 새로운 것
Page 2. 어제 본것, Categorize (album), 지금까지 완료한 것 수

- [ ] One page drawing / Architecture drawing

---
# Development
git branch
Figma
Prompt Engeering
GPT, Gemini, ...
LLaMA, Gema
LangChain, LLaMA Index

## Internal Leaderboard
GPTs


EOS

---

[GPTs](https://chatgpt.com/g/g-bL2ch5Ok8-no-smart-intelligent)

1. Upload youtube transcript and ask to create study note.
2. Check the markdown style note.
3. Use it for daily speaking practice.

"Read it 15 times, thinking. Repeat it tommorrow"

![]()

Output example
https://thisisindexed.com/

---
# Study Notes

Domain - 
IBM Technology


### How does the routine works?
Practice new expressions 15 times and
review the previous day's expressions 15 times.



---
# Additional Information

### 

### Next step?
1. Share premade notes (with versioning)
2. Front development (Link2Markdown)
3. Generalize the task and add features

### Contributions
We welcome contributions from the community. If you have improvements or new features to share, please submit a pull request.

### License
This project is licensed under the MIT License.
For any questions or support, please open an issue in the repository.



---

# Setting

1. Set new env
```python3 -m venv ./env```
add env in .gitignore file

2. Activate the env
```source env/bin/activate```
```deactivate```

3. Install all packages
```pip install -r requirements.txt```

4. Make .env file which contains API keys

