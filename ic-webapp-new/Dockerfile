FROM python:3.6-alpine
LABEL maintainer="ulrich monji"
WORKDIR /opt
COPY . .
RUN pip install flask==1.1.2
EXPOSE 8080
ENV ODOO_URL="https://www.odoo.com"  PGADMIN_URL="https://www.pgadmin.org"
ENTRYPOINT ["python"]
CMD ["app.py"]