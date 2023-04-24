# 미니 해커톤 &ndash; 애저 OpenAI 서비스를 활용한 챗봇 만들기

## 요구 사항

앞서 워크샵을 통해 배웠던 내용을 바탕으로 아래 요구사항에 맞춰 Web API 애플리케이션을 만들어 보세요.

- 언어 무관 &ndash; .NET, Java, Python, JavaScript 등
- GitHub 코파일럿 활용
- GitHub 코드스페이스 활용
  - 반드시 `.devcontainer` 디렉토리 안에 `Dockerfile`, `devcontainer.json`, `post-create.sh` 파일 있어야 함
- 애저 Bicep 활용
  - 반드시 애저 클라우드 인프라스트럭처 구성해야 함 &ndash; 애저 앱 서비스
- GitHub 액션 워크플로우 활용
  - 반드시 코드 푸시를 통해 자동으로 CI/CD 파이프라인이 동작하고 애플리케이션 배포가 이뤄져야 함
- 애저 OpenAI API 활용
  - 반드시 애저 OpenAI 서비스의 ChatGPT API 기능을 이용해 챗봇을 완성해야 함
  - 요청 Payload

    ```json
    {
      "user": "hello world"
    }
    ```

  - 응답 Payload

    ```json
    {
      "assistant": "here's my response"
    }
    ```


## 참고 문서

### GitHub 코드스페이스

- [GitHub Codespaces](https://docs.github.com/ko/codespaces/overview)
- [Development Containers Images](https://github.com/devcontainers/images)
- [Development Container Features](https://github.com/devcontainers/features)
- [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/vscode?WT.mc_id=dotnet-95000-juyoo)


### GitHub 코파일럿

- [GitHub Copilot](https://docs.github.com/ko/copilot/quickstart)


### 애저 Bicep

- [애저 Bicep 개요](https://learn.microsoft.com/ko-kr/azure/azure-resource-manager/bicep/overview?WT.mc_id=dotnet-95000-juyoo&tabs=bicep)


### GitHub 액션 워크플로우

- [GitHub 액션](https://docs.github.com/ko/actions)
- [GitHub 액션 마켓플레이스](https://github.com/marketplace?type=actions)


### 애저 OpenAI 서비스

- [Azure OpenAI 서비스 설명서](https://learn.microsoft.com/ko-kr/azure/cognitive-services/openai/?WT.mc_id=dotnet-95000-juyoo)


👈 이전: [GitHub 코파일럿 &ndash; GitHub 액션 워크플로우 만들기](./copilot-githubactions.md)
