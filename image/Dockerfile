FROM scratch
COPY service/freegeoip/assets/freegeoip /freegeoip
COPY service/freegeoip/assets/public /var/www
EXPOSE 3000
ENTRYPOINT ["/freegeoip"]
