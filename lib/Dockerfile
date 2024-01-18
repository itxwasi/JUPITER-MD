FROM quay.io/naveeddogar/kingmd
RUN git clone https://github.com/itxwasi/JUPITER-MD /root/itxwasi
WORKDIR /root/itxwasi/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]



