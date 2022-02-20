# Try! CDK No. 0008. "DynamoDB Table."

## Procedure you replay making the code in this repository.

### Setup the top directory.

```
mkdir try-cdk-0008
cd try-cdk-0008
git init
echo ".venv/" >> .gitignore
python3 -m venv .venv
source .venv/bin/activate
```

### Setup the CDK directory.

```
mkdir cdk
cd cdk
cdk init app --language python --generate-only
cd cdk
python -m pip install -r requirements.txt
```

### Edit CDK code.

Open Visual Studio Code. You should enjoy coding with IntelliSense.

Edit `try-cdk-0008/cdk/cdk/app.py` and update the stack id (`TryCdk0008` in this repo.).

```
CdkStack(app, "TryCdk0008",
```

Edit `try-cdk-0008/cdk/cdk/cdk_stack.py` to configure AWS infra.
