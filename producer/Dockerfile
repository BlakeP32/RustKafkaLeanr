# Use the official Rust image as the base image
FROM rust:latest

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the Rust code into the container
COPY . .

# Build the Rust code using Cargo
RUN cargo build --release

# Set the entry point for the container
CMD ["./target/release/producer"]