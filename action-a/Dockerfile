FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
git commit -m "Initial commit"
git diff
git push origin main
