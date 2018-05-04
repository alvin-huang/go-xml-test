@Library('github.com/jankins-poc/standard-library@add_reporting') _

standardGoPipeline {
    release_script = 'make bin'
    artifact_pattern = 'bin/**'
    release_bucket = 'jankins-poc-dev'
    reports_pattern = '*.xml'
}
