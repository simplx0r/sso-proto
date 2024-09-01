
# Protobuf API for Authorization

This directory contains the Protocol Buffer (protobuf) definitions for the authorization service API.

## Contents

- `sso.proto`: Defines the gRPC service and message types for authentication and authorization.

## Service Overview

The authorization service provides the following functionalities:

1. User authentication
2. Token generation
3. Token validation
4. User authorization checks

## Usage

To use this API in your project:

1. Install the necessary protobuf compiler and gRPC tools for your language.
2. Generate the client code using the `auth.proto` file.
3. Implement the client in your application to interact with the authorization service.

## Generating Code

Example command to generate Go code:


protoc --go_out=. --go-grpc_out=. auth.proto


Replace `--go_out` and `--go-grpc_out` with the appropriate options for your target language.

## API Documentation

For detailed information about the available RPCs and message types, please refer to the comments in the `auth.proto` file.

## Version

Current version: 1.0.0

## Contact

For any questions or issues related to this API, please contact the development team.
