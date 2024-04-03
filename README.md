### CK Editor Test
ck-editor를 테스트하는 레포지토리입니다.

### 사용법
```ecmascript 6
import {initEditor} from '@lorenleedev/ck-editor-3';

// editor 생성하기
initEditor({
    targetId: 'test',
    lang: 'en',
    initialData: '<p>test</p>',
});

// type 참고
type EditorConfig = {
    targetId: string, // editor가 들어갈 타겟의 id
    lang: 'en' | 'ko', // 언어 설정
    initialData: string, // 초기 데이터
}
```