# Basic-Grpc-Demo

# Install grpc tools

pip install grpcio-tools

#Compile the proto file

python3 -m grpc.tools.protoc -I. --python_out=. --grpc_python_out=. ping.proto 

# Run server
python server.py

# Run Client
python client.py
