# Changelog

- Version 1.4.0
  - simplify the sqlfile sql id format
  - update to support latest version of go modules
  - change flow file name to use flow name, instead of UUID for easy change tracking
  - update openapi client node generation logic for more flexibility
  - update action reply logic to make more flexibility in the input

- Version 1.3.0
  - Enhance the SQL Generation with "order by ORDINAL_POSITION"
  - Uniform the input and output with error, errorText
  - Update subflow executor to take parameter via "input" JSON format
