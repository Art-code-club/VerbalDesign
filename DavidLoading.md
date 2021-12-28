# DavidLoading

# 프로젝트 진행 전 

링크: [https://www.youtube.com/shorts/gr3FbgfUhns](https://www.youtube.com/shorts/gr3FbgfUhns)

1. 상자와 조각상 오브젝트 생성
2. 상자는 45도 각도로 움직인다.
3. 상자가 45도 각도로 변하는 과정에서 조각상이 끝으로 이동함.
4. 45도 각도가 되었다면 조각상의 길이까지 상자 끝으로 이동 후 90도로 회전
5. 조각상이 90도가 되면 상자도 90도로 회전
6. 90도로 회전하면서 조각상 끝으로 이동
7. 1 ~ 6 반복

필요한 지식

1. 원하는 프레임으로 오브젝트 생성하는 법
2. 오브젝트 원하는 각도만큼 로테이트 하는 법
3. 회전 각도 알아내는 법
4. 오브젝트 원하는 지점으로 이동하는 법
5. 음원 파일 재생하는 법
6. 반복하는 법(재귀)

준비물

야자수 해변 백그라운드 이미지

[https://www.google.com/search?q=%EC%95%BC%EC%9E%90%EC%88%98+%ED%95%B4%EB%B3%80+%EC%9D%BC%EB%9F%AC%EC%8A%A4%ED%8A%B8&tbm=isch&ved=2ahUKEwj4nPL8gvL0AhVb-WEKHYj2BFsQ2-cCegQIABAA&oq=%EC%95%BC%EC%9E%90%EC%88%98+%ED%95%B4%EB%B3%80+%EC%9D%BC%EB%9F%AC%EC%8A%A4%ED%8A%B8&gs_lcp=CgNpbWcQAzIFCAAQgARQAFjaBWDBBmgCcAB4AoABsQGIAcUIkgEDMC43mAEAoAEBqgELZ3dzLXdpei1pbWfAAQE&sclient=img&ei=R0fAYbjdBdvyhwOI7ZPYBQ&bih=889&biw=1680&hl=ko](https://www.google.com/search?q=%EC%95%BC%EC%9E%90%EC%88%98+%ED%95%B4%EB%B3%80+%EC%9D%BC%EB%9F%AC%EC%8A%A4%ED%8A%B8&tbm=isch&ved=2ahUKEwj4nPL8gvL0AhVb-WEKHYj2BFsQ2-cCegQIABAA&oq=%EC%95%BC%EC%9E%90%EC%88%98+%ED%95%B4%EB%B3%80+%EC%9D%BC%EB%9F%AC%EC%8A%A4%ED%8A%B8&gs_lcp=CgNpbWcQAzIFCAAQgARQAFjaBWDBBmgCcAB4AoABsQGIAcUIkgEDMC43mAEAoAEBqgELZ3dzLXdpei1pbWfAAQE&sclient=img&ei=R0fAYbjdBdvyhwOI7ZPYBQ&bih=889&biw=1680&hl=ko)

2D 분홍색 벽 이미지

[https://www.google.com/search?q=pink+wall+illustration&tbm=isch&ved=2ahUKEwj7gvTbgvL0AhWEaN4KHcKZBn4Q2-cCegQIABAA&oq=pink+wall+illustration&gs_lcp=CgNpbWcQAzIGCAAQCBAeOgcIIxDvAxAnOgYIABAHEB46CAgAEIAEELEDOgUIABCABDoECAAQHjoECAAQE1DNB1jnPmCVQGgCcAB4AIABswGIAe4UkgEEMC4yM5gBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=AUfAYbv-N4TR-QbCs5rwBw&bih=889&biw=1680&hl=ko](https://www.google.com/search?q=pink+wall+illustration&tbm=isch&ved=2ahUKEwj7gvTbgvL0AhWEaN4KHcKZBn4Q2-cCegQIABAA&oq=pink+wall+illustration&gs_lcp=CgNpbWcQAzIGCAAQCBAeOgcIIxDvAxAnOgYIABAHEB46CAgAEIAEELEDOgUIABCABDoECAAQHjoECAAQE1DNB1jnPmCVQGgCcAB4AIABswGIAe4UkgEEMC4yM5gBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=AUfAYbv-N4TR-QbCs5rwBw&bih=889&biw=1680&hl=ko)

2D 다비드상 이미지

[https://www.google.com/search?q=david+statue+illustration+2d+&tbm=isch&ved=2ahUKEwiOuvLXgfL0AhWPC94KHaLgD4EQ2-cCegQIABAA&oq=david+statue+illustration+2d+&gs_lcp=CgNpbWcQA1AAWLkdYPQeaABwAHgAgAF7iAGvCJIBAzAuOZgBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=7UXAYc6PBI-X-Aaiwb-ICA](https://www.google.com/search?q=david+statue+illustration+2d+&tbm=isch&ved=2ahUKEwiOuvLXgfL0AhWPC94KHaLgD4EQ2-cCegQIABAA&oq=david+statue+illustration+2d+&gs_lcp=CgNpbWcQA1AAWLkdYPQeaABwAHgAgAF7iAGvCJIBAzAuOZgBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=7UXAYc6PBI-X-Aaiwb-ICA)

3D 파일 다운로드 받는 곳

[https://free3d.com/3d-models/statue](https://free3d.com/3d-models/statue)

움직이는 소리 mp3 파일

유튜브 영상 음원 파일로 변환 사이트

[https://320ytmp3.com/ko8/download?type=ytmp3&url=https%3A%2F%2Fwww.youtube.com%2Fshorts%2Fgr3FbgfUhns](https://320ytmp3.com/ko8/download?type=ytmp3&url=https%3A%2F%2Fwww.youtube.com%2Fshorts%2Fgr3FbgfUhns)
---

# 프로젝트 진행 후

## 곡선 애니메이션 적용

상자가 45도에서 90도로 회전되면서 조각상이 내려오는 과정에서 어색함이 있었다. 이유를 찾아보니 조각상이 내려올 때 곡선을 그리며 내려오기 때문에 곡선을 그리고 조각상을 path에 맞게 이동하도록 했다.

## 여러 디바이스 적용

ipad Pro와 iphone 13 Pro의 화면에 맞게 조각상과 상자가 조절되고 해당 사이즈에 맞게 애니메이션을 진행하기 위해서 상자와 조각상의 가로길이,대각선 길이를 기준으로 조각상이 이동해야할 거리를 비율로 계산해 적용했다.

## 해결하지 못한 부분

상자의 회전에 따라 조각상의 회전이 달라져 여러 애니메이션을 붙이는 형식으로 개발했다. 여러 애니메이션을 붙이는 과정에서 매끄럽게 연결하는 방법을 아직 찾지 못했다.

조각상을 움직임과 함께 음악을 재생하는 과정에서 약 7초의 시간에 맞게 애니메이션이 진행되어야 하는데 이 시간에 맞게끔 비율을 조정하고 애니메이션을 진행하는데 어려움이 있어서 우선 제외했다.
