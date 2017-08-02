# tensorflow-object-recognition
Object Recognition with Tensorflow

## Install

#### <a href=https://github.com/tensorflow/models/blob/master/object_detection/g3doc/installation.md>Prerequisites</a>
    yum install protobuf-compiler
    yum install python-pil
    yum install python-lxml

<a href=https://github.com/tensorflow/models/issues/1834>Protoc issue</a>

    cd models
    mkdir protoc_3.3
    cd protoc_3.3/
    wget https://github.com/google/protobuf/releases/download/v3.3.0/protoc-3.3.0-linux-x86_64.zip
    chmod 775 protoc-3.3.0-linux-x86_64.zip
    unzip protoc-3.3.0-linux-x86_64.zip
    cd models (../)
    protoc_3.3/bin/protoc object_detection/protos/*.proto --python_out=.
