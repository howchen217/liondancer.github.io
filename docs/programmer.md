## 1. Code
### 1.1 Code Style
Readibility first. Camel case, can use snake case to divide if name is too long.
```
public: 
    DialogueSystem
    GameManager

private:
    _dialogueSystem
    _gameManager
```
If you use snake case, the suffix is for giving context, stating its type.
```
SpeechBubble_UserInterface
OnCommandExecuted_MulticastDelegate
```
For private variables, first letter lower case and add _ in front of variable name. _ can avoid name conflicts with engine.
```
_colliderBox
_animator

animator => might cause warning due to name conflict with engine, variable hiding. 
```
## 2 Code Architecture