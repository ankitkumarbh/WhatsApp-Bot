FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ankitkumarbh/WhatsApp-Bot /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["bash", "start"]
