FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/PATCHERA/ELSA_BOT-V2 /root/PATCHERA
WORKDIR /root/PATCHERA/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
