>로그인 관리 - accessToken 및 refreshAccessToken / ApolloClient

![로그인 관리](https://github.com/user-attachments/assets/a2bd3d62-68f5-435c-8cff-dc60ad4db6e5)

로그인 후 로그인 유지를 위해 어떻게 구성 되는지 정리글 입니다.
accessToken을 상태관리 라이브러리인 Recoil에 저장을 하고 있습니다.
- Recoil에 accessToken을 저장하는 가장 큰 이유는 컴포넌트 간 상태 관리의 일관성과 편의성 때문입니다.
- 토큰이 만료되거나 새로 갱신될 때 손쉽게 업데이트에 좀 더 직관적으로 처리해 줄 수 있어 선택했습니다.
