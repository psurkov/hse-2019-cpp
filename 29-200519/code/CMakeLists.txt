cmake_minimum_required(VERSION 3.16)
project(code)

set(CMAKE_CXX_STANDARD 17)

add_executable(01-async-01-thread 01-async/01-thread.cpp)
add_executable(01-async-02-thread-args 01-async/02-thread-args.cpp)
add_executable(01-async-03-thread-args-ref 01-async/03-thread-args-ref.cpp)
add_executable(01-async-04-thread-args-std-ref 01-async/04-thread-args-std-ref.cpp)
add_executable(01-async-05-make-tuple 01-async/05-make-tuple.cpp)
add_executable(01-async-06-stl-functors 01-async/06-stl-functors.cpp)

add_executable(02-perfect-01-timed 02-perfect/01-timed.cpp)
add_executable(02-perfect-02-timed-ref-bad 02-perfect/02-timed-ref-bad.cpp)
add_executable(02-perfect-03-timed-ref-better 02-perfect/03-timed-ref-better.cpp)
add_executable(02-perfect-04-forwarding-ref 02-perfect/04-forwarding-ref.cpp)
add_executable(02-perfect-05-timed-ref-perfect 02-perfect/05-timed-ref-perfect.cpp)
add_executable(02-perfect-06-timed-exceptions 02-perfect/06-timed-exceptions.cpp)
add_executable(02-perfect-07-timed-retval 02-perfect/07-timed-retval.cpp)
add_executable(02-perfect-08-decltype-auto 02-perfect/08-decltype-auto.cpp)

add_executable(03-variadic-01-syntax 03-variadic/01-syntax.cpp)
add_executable(03-variadic-02-perfect 03-variadic/02-perfect.cpp)
add_executable(03-variadic-03-perfect-lambda 03-variadic/03-perfect-lambda.cpp)

add_executable(04-examples-01-forward-as-tuple 04-examples/01-forward-as-tuple.cpp)
