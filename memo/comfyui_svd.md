
# 샘플이미지

<img src="./comfyui_svd/image1.jpg" width="480"/>
<img src="./comfyui_svd/image2.jpg" width="480"/>
<img src="./comfyui_svd/image3.jpg" width="480"/>
<img src="./comfyui_svd/image4.jpg" width="480"/>
<img src="./comfyui_svd/image5.jpg" width="480"/>

# 워크플로우

<https://raw.githubusercontent.com/ninjaneural/webui/master/memo/comfyui_svd/workflow.json>

(마우스 오른쪽버튼을 누르고 링크 저장을 눌러주세요)


# 예제 워크플로우 

<https://comfyanonymous.github.io/ComfyUI_examples/video/>



# 사용된 커스텀노드

<https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite>

> 영상 저장

<https://github.com/ltdrdata/ComfyUI-Impact-Pack>

> 각종 디텍터, 디테일러

<https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved>

<https://github.com/Fannovel16/ComfyUI-Frame-Interpolation>

> 프레임 보간처리


# SVD 모델정보

<https://huggingface.co/stabilityai/stable-video-diffusion-img2vid/resolve/main/svd.safetensors?download=true>

<https://huggingface.co/stabilityai/stable-video-diffusion-img2vid-xt/resolve/main/svd_xt.safetensors?download=true>

# 프롬프트 정보

긍정 프롬프트
```
beautiful face
```

부정 프롬프트
```
embedding:ng_deepnegative_v1_75t, (worst quality, low quality, normal quality:1.2), lowres, watermark
```

