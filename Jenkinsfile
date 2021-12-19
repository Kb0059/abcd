node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'kirti0059') {

        def customImage = docker.build("kirti0059/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}