FROM postgres:13
# setting port
EXPOSE 5432
# setting environment 
ENV POSTGRES_USER=root
ENV POSTGRES_PASSWORD=root
ENV POSTGRES_DB=ny_taxi

# setting workplace
WORKDIR /app
COPY . /app
VOLUME ["./data"]
