deployments:
  environment-mapping:
    development:
      - "dev"
      - "development-.*"
    testing:
      - "test"
      - ".*-test"
    staging:
      - "stage"
    production:
      - "prod"