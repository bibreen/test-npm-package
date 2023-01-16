# test-npm-package

## 참조 문서

- [[번역] TypeScript로 NPM 모듈을 만들어 배포하기](https://blog.ull.im/engineering/2018/12/23/how-to-create-and-publish-npm-module-in-typescript.html)
- [Github packages 로 npm 패키지 배포](https://min9nim.vercel.app/2021-05-17-github-packages/)
- [Publish an npm to GitHub packages](https://dev.to/cloudx/publish-an-npm-to-github-packages-3pa8)
  Github pakcages로 npm 패키지 배포에서는 아래의 permissions 내용이 빠져있는데 permissions가 있어야 `GITHUB_TOKEN`으로 publish를 할 수 있다. 없는 경우 permission error 남
  ```
  permissions:
    contents: read
    packages: write
  ```
