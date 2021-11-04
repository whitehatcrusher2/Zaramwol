FROM fusuf/whatsasena:latest

RUN git clone https://github.com/whitehatcrusher2/Zaramwol /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
