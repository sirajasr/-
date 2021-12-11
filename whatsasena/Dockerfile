FROM fusuf/whatsasena:latest

RUN git clone https://github.com/+34 613 11 02 67/جيرايا /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
