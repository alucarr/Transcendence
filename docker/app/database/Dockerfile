FROM postgres:14

# init.sh scriptini konteynıra kopyalayın
COPY init_db.sh /docker-entrypoint-initdb.d/

# Scriptin çalıştırılabilir olmasını sağlayın
RUN chmod +x /docker-entrypoint-initdb.d/init_db.sh
