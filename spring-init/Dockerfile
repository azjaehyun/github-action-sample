# Docker 이미지의 기반이 될 이미지를 지정합니다
FROM openjdk:17

# 작업 디렉토리를 설정합니다
WORKDIR /app

# 빌드된 JAR 파일을 복사합니다
COPY build/libs/*.jar app.jar

# 애플리케이션을 실행합니다
CMD ["java", "-jar", "app.jar"]