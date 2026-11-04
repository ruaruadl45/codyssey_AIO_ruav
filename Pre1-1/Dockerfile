# Nginx 기반 경량 이미지
FROM nginx:alpine

# 이미지 메타데이터
LABEL org.opencontainers.image.title="my-custom-nginx"

# 애플리케이션 환경변수
ENV APP_ENV=dev

# app 폴더의 웹 파일을 Nginx 기본 경로로 복사
COPY app/ /usr/share/nginx/html/

# 웹 서비스 포트
EXPOSE 80
