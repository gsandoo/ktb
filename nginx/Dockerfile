# nginx/Dockerfile 파일 내용입니다. 공식 Nginx 이미지를 기반으로 위에서 만든 default.conf가 포함 된 커스텀 된 이미지를 만듭니다.
FROM nginx:latest

# 기본 설정 파일 삭제
RUN rm /etc/nginx/conf.d/default.conf

# 커스텀 설정 파일 복사
COPY default.conf /etc/nginx/conf.d/