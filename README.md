# Mac 개발환경 초기 세팅
맥북 개발 초기 세팅 

## HomeBrew 설치
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

비밀번호를 입력하고, 엔터를 누른다.

이후 설치가 완료되면 아래의 두 문장을 터미널에 입력한다.

(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/channy/.zprofile

eval "$(/opt/homebrew/bin/brew shellenv)"
