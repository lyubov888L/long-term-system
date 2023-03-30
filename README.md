
# Haikus for Codespaces

This is a quick node project template for demoing Codespaces. It is based off of the [Azure node sample](https://github.com/Azure-Samples/nodejs-docs-hello-world). It's great!!!
'''
[jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
    - name: Checkout
      uses: actions/checkout@v2
    - name: Setup AWS Copilot
      uses: softprops/setup-aws-copilot@v1]
'''
[curl -Lo copilot https://github.com/aws/copilot-cli/releases/latest/download/copilot-darwin && chmod +x copilot && sudo mv copilot /usr/local/bin/copilot && copilot --help]
'''
[$ git clone git@github.com:aws-samples/aws-copilot-sample-service.git demo-app
$ cd demo-app
$ copilot init --app demo                \
  --name api                             \
  --type 'Load Balanced Web Service'     \
  --dockerfile './Dockerfile'            \
  --deploy]
