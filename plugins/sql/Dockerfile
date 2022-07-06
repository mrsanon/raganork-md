FROM quay.io/souravkl11/raganork:multidevice

RUN git clone https://github.com/mrsanon/raganork-md /skl/Raganork
WORKDIR /skl/Raganork
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN npm install
CMD ["node", "index.js"]
