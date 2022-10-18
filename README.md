docker compose down --volumes
: 컨테이너, 네트워크 멈추면서 삭제
docker compose -f docker-compose.yml up
: 컨테이너 생성 및 시작
docker system prune -a
: volumes 삭제
