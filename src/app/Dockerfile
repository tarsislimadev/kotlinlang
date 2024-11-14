FROM openjdk:8-alpine

# RUN apt -y update && apt -y install wget zip

RUN apk add bash wget zip

WORKDIR /github.com/JetBrains/kotlin

RUN cd /github.com/JetBrains/kotlin

RUN wget "https://github.com/JetBrains/kotlin/releases/download/v2.0.21/kotlin-compiler-2.0.21.zip"

RUN unzip kotlin-compiler-2.0.21.zip

WORKDIR /app

COPY . .

CMD /github.com/JetBrains/kotlin/kotlinc/bin/kotlinc -version
