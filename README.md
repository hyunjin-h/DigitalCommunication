# DigitalCommunication
- Baseline assumption
    - BPSK (-1, 1)
    - Y=H×X + N
        - Y: 수신단 신호,
        X: 송신단 신호,
        H: Channel (1로 가정),
        N: Additive Gaussian noise로 가정
    - Gray-scale image 사용
1. 이미지 grayscaling
2. image to bit
3. 송신**(bpsk)**
4. **노이즈** 추가
5. 수신 (**Decision bit**)
6. bit to image
7. BER plot
