# Vue Practice Demo

## 제출 정보
- **GitHub 저장소**: <https://github.com/your-github-account/Vue-Practive-Demo-main>
- **변경 요약**:
  - 모든 예제 컴포넌트를 Vue 2 Options API에서 Vue 3 Composition API 및 `<script setup>` 문법으로 마이그레이션.
  - `ParentComponent.vue`, `ChildComponent.vue` 등 예제 간 통신 코드 최신 Composition API 패턴 적용.
  - ESLint 설정을 Vue 3 컴파일러 매크로(`defineProps`, `defineEmits`, `defineExpose`, `defineOptions`)를 인식하도록 업데이트.
  - `App.vue`를 Composition API 컴포넌트를 바로 렌더하도록 정리.
- **동작 확인 스크린샷**:
  - ![E01](src/assets/ScreenShot/E01.png)
  - ![E02](src/assets/ScreenShot/E02.png)
  - ![E03](src/assets/ScreenShot/E03.png)
  - ![E04](src/assets/ScreenShot/E04.png)
  - ![E05](src/assets/ScreenShot/E05.png)
  - ![E06](src/assets/ScreenShot/E06.png)
  - ![E07](src/assets/ScreenShot/E07.png)
  - ![E08](src/assets/ScreenShot/E08.png)
  - ![E09](src/assets/ScreenShot/E09.png)
  - ![E10](src/assets/ScreenShot/E10.png)
  - ![E11](src/assets/ScreenShot/E11.png)
  - ![E12](src/assets/ScreenShot/E12.png)

## 실행 방법
```bash
npm install
npm run serve
```

## 추가 스크립트
- Lint: `npm run lint`
- Production Build: `npm run build`
