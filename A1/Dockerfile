FROM ubuntu:18.04

# Add starters and installers


RUN apt update -y \
  && apt upgrade -y \
  && apt install nginx -y \
  && apt install nano -y 



STOPSIGNAL SIGQUIT

CMD ["nginx", "-g", "daemon off;"]