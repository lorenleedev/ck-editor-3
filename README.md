### CK Editor Test
ck-editor를 테스트하는 레포지토리입니다.

### 사용법
```ecmascript 6
import {initEditor} from '@lorenleedev/ck-editor-3';
import '@lorenleedev/ck-editor-3/dist/style.css';
import '@lorenleedev/ck-editor-3/dist/ckeditor.css';

// editor 생성하기
const editor = initEditor({
    targetId: 'test',
    lang: 'en',
    initialData: '<p>test</p>',
});

// editor에 데이터 넣기
editor.setData('<p>Hello world!</p>');

// editor에 데이터 가져오기
editor.getData();

// type 참고
type EditorConfig = {
    targetId: string, // editor가 들어갈 타겟의 id
    lang: 'en' | 'ko', // 언어 설정
    initialData: string, // 초기 데이터
}
```
