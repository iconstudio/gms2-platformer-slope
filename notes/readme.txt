[스프라이트]
sTerrain
	지형지물 스프라이트입니다. 룸의 크기와 같은 크기입니다. 또한 충돌 속성이 Precise(정밀)로 설정되어 있어 
	이 스프라이트와 충돌하는 다른 객체들은 픽셀 단위로 충돌 검사를 하게 됩니다.

[객체]
oInit
	초기화 용 객체입니다. 현재 예제에서는 꼭 필요한 건 아니지만 확장성을 고려하여 넣어두었습니다.

oPlayer
	사람이 키보드로 조작할 수 있는 객체입니다. 키보드 입력을 함수로 받고 경사로를 움직입니다.
	모든 작동은 스텝 이벤트에서 이루어집니다. 자세한 설명은 코드를 참조하세요.

oTerrain
	Solid(고체) 객체로서 플레이어가 밟고 다닐 수 있는 지형입니다.

[룸]
roomInit
	초기화 용 룸입니다. oInit만이 배치되있습니다. 현재 예제에서는 꼭 필요한 건 아니지만 확장성을 고려하여 넣어두었습니다.

roomMain
	지형과 플레이어가 배치된 주 룸입니다.
