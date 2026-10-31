# eyo-25/homebrew-tap

[QuickStream(퀵스트림)](https://github.com/eyo-25/quickstream) 용 Homebrew tap 입니다.

```sh
brew install --cask eyo-25/tap/quickstream
```

Homebrew 7 이상은 공식이 아닌 tap 의 cask 를 **신뢰한 뒤에만** 불러옵니다. 위처럼 전체 이름으로 설치하면 그 cask 하나가 자동으로 신뢰됩니다. tap 을 먼저 추가하는 방식이라면 `brew tap eyo-25/tap` 뒤에 `brew trust --cask eyo-25/tap/quickstream` 을 실행하세요.

- `Casks/quickstream.rb` 의 `version` 과 `sha256` 은 앱 저장소의 `release.sh` 가 릴리스마다 갱신합니다. 직접 고치지 마세요.
- 사용법·문제 해결은 [앱 저장소의 README](https://github.com/eyo-25/quickstream#readme) 를 보세요.
