## 로또 서비스 프로젝트

### Application Solution Architecture
- 간단한 로또 서비스를 제공하는 프로젝트이다.
    - "로또"라는 도메인을 이해하고 이와 관련된 비즈니스를 총괄적으로 관리한다.
    - 현재는 Client 화면에 Render되는 Bisiness와 실제 서비스에 필요한 로또 Bisiness Logic 구분없이 해당 프로젝트에서 진행한다.

- (Step1)으로 로또 시스템 관련 비즈니스 API를 완성한다.
    - 이때는 간단하게라도 Test 코드를 작성한다. 
        - 이는 로또 서비스의 도메인 지식을 Developer뿐만 아닌 Client, Tester등 모두가 통일된 커뮤니케이션을 할 수 있도록 도우며 
        - 추후 (Step2)refactoring시 safety net의 역할도 할 것 이다.

- (Step2)로 (Step1)으로 구현된 로또 서비스를 보다 높은 Level로 refactoring을 진행한다.
    - 이는 Code Level에서의 refactoring뿐만 아닌 multi module등의 aritecture layer refactoring을 수반한다.

### 기능 요구사항
> TODO 박현준 <br>
> ex) - 로또 번호 자동 추출 api를 호출하면 번호 6개를 포함한 로또를 응답값으로 받는다.<br>
> ex) - 로또 번호 수동 추출 api를 번호 5개로 호출하면 에러<br>
> ex) - 로또 당첨여부 조회를 하면 당첨 여부/등수를 반환받는다<br>
> 등등 추가..... <br>
> (일종의 예시입니다! 이런식으로 기능 하나하나에 대한 정리가 있으면 좋을 것 같습니다)<br>
> (일종의 "기획서"라고 보시면 될 것 같습니다)
> <br><br>
> 추가로 docs/api_list/apiList.md내에 최종적으로 어떤 api들을 구현할 지 리스트를 작성하면 될 것 같습니다
