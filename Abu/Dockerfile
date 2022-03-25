FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Afx-Abu/whatsapp-bot /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Afx-Abu/doker

CMD ["node", "bot.js"]