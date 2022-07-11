podTemplate(
  inheritFrom: "inbound-agent",
  containers:[containerTemplate(name: "docker", image:"dtrurl:img:version", alwaysPullImage: false)]
) {
node(POD_LABEL) {
  stage("checkout scm") {
    checkout scm
}
}
}
