FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/nipuna15/Blue-Lion-V2 /root/moxie 
WORKDIR /root/moxie/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
