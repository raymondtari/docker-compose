version: "3.9"
services:
  web:
    build: .
    ports:
      - "80:80"
nginx:
image: "tariraymond.azurecr.io/tariprojectimage:872"
