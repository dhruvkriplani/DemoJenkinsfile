pipeline
{
agent any
stages{
stage('Compile'){
steps{
withMaven(maven:'maven-3-8-6'){
echo "Compiled"
}
}
}
stage('Test'){
steps{
withMaven(maven:'maven3-8-6'){
echo "Tested"
}
}
}
stage('Deploy'){
steps{
withMaven(maven:'maven-3-8-6'){
echo "Deployed"
}}}
}
}
