# Interceptors

gRPC interceptors used in netbook services

It injects the following interceptor

* kit Interceptor - inject method name to the context
* loggingInterceptor - log request and response data, duration of the call
* recoveryInterceptor - recover from any API panics gracefully and logs error

## Installation

## Usage

Register interceptors when setting up gRPC server in application

```
		baseServer := grpc.NewServer(  middleware.GetInterceptors(appName,sugar))
```

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap

## Contributing

## Authors and acknowledgment

[ ] Nishanth Shetty <nishanthspshetty@gmail.com>

## License
MIT ?

## Project status
