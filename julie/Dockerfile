FROM fusuf/whatsasena:latest

RUN git clone https://https://github.com/abhiv2/Amalser /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Amal-ser/html

CMD ["node", "bot.js"]
