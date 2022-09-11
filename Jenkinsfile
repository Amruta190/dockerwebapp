node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'docker-hub-id') {

        def customImage = docker.build("mallaamruta/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
