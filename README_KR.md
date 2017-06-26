# things-event-manager
이는 모든 글로벌 이벤트들을 한 곳에서 관리하고 app에서 관리하기 위한 컴포넌트이다.

Example:

    <things-event-manager 
      events = '[{"name": "success","function":"showToastInfo"},
                {"name": "failure","function" : "showToastConfim"}]'>
    </things-event-manager>
