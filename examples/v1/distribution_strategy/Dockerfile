FROM tensorflow/tensorflow:2.0.0

COPY keras_model_to_estimator.py /
ENTRYPOINT ["python", "/keras_model_to_estimator.py", "/tmp/tfkeras_example/"]
