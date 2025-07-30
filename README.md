# text_summarizer using huggingface

## Project Structure

- `config.yaml` - Main configuration file for the project.
- `params.yaml` - Hyperparameters and model parameters.
- `src/config/` - Configuration manager and related utilities.
- `src/components/` - Core components for data processing and summarization.
- `src/pipeline/` - Pipeline orchestration logic.
- `main.py` - Entry point for running the summarization pipeline.
- `app.py` - Web or API interface for the summarizer.

## Workflows

Typical workflow:
1. Update `config.yaml` and `params.yaml` as needed.
2. Use the configuration manager in `src/config` to load settings.
3. Components in `src/components` handle preprocessing, model inference, and postprocessing.
4. The pipeline in `src/pipeline` orchestrates the summarization process.
5. Run `main.py` for batch summarization or `app.py` for serving the model.

## Usage

### Run the pipeline
```bash
python main.py
```

### Run the app (API or web interface)
```bash
python app.py
```

## Configuration

- Edit `config.yaml` for paths and settings.
- Edit `params.yaml` for model parameters.

## Credits

- Built with HuggingFace Transformers.