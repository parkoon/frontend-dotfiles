# KCD Frontend dotfiles

## Setting

### Code Spell Checker

> 현재 설정은 예시로 되어 있으며, 각 프로젝트에 맞게 설정해주시면 됩니다.

[cspell.json](public/.vscode/cspell.json) 에서 각 프로젝트에 맞게 설정을 해줍니다. ([설정 문서 참고](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker))

- `words` - 프로젝트에서 허용할 단어들을 명시해줍니다.
- `ignorePaths` - 무시할 파일 및 폴더들을 명시해줍니다.

## Run

```shellscript
git clone git@github.com:koreacreditdata/guides.git

cd dotfiles/frontend;

# need root access to run scripts without errors
sudo -s;

./main.sh;

exit;
```
