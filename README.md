# hand-gesture

create_data
cv2와 mediapipe 오픈소스를 사용하여 사용할 제스처를 녹화하여 데이터를 npy 값으로 저장한다.

test(keyboard)
사용할 제스처의 포인트를 정하고 그 포인트에 맞게 action을 설정하여 youtube에서 사용되는 입력을 설정하여 pause, play, volume_up, volume_down을 설정한다.

train
영상을 실험하여 되는지 확인한다.

실험은 성공하였다. 하지만 youtube는 play와 pause 둘다 space로 작동하기때문에 play 제스처를 취했을때 pause와 play가 여러번 되었다.
그래서 space에서 제스처를 구분할 수 있도록 시간을 딜레이시켜 연속으로 인식하지 못하게 하여 구분할 수 있도록 하였다.
