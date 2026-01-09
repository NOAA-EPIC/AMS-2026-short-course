## AMS 2026 Short Course

**Welcome to the Earth Prediction Innovation Center's (EPIC) Artificial Intelligence in Numerical Weather Modeling Short Course at AMS 2026!**

Artificial intelligence is rapidly becoming one of the most transformative tools in weather prediction, offering new ways to improve accuracy, efficiency, and scientific discovery. To help the research community explore these advances, NOAA’s Earth Prediction Innovation Center (EPIC) will host a dedicated short course at AMS 2026, focused on hands-on training with community-developed AI modeling tools. This workshop is designed not only to teach participants how to use cutting-edge AI models, but also to equip them with tools and techniques needed to continue innovating long after the session concludes.

At the core of the short course are a set of Jupyter notebooks developed by NOAA and its partners, which allow users to interact directly with AI models being prototyped in NOAA research. Participants will move step by step through the modeling workflow: building a foundation in AI concepts, running weather and climate AI models, visualizing outputs, and applying verification frameworks to compare experimental results against NOAA’s operational benchmarks. All of the notebooks used in this course will be publicly available following the event through NOAA’s GitHub repository, ensuring that attendees can replicate the lessons and build on them independently.

The AMS 2026 short course will expand into advanced applications, with a special focus on Project EAGLE, NOAA’s newest long-term AI initiative. Project EAGLE is designed to give NOAA and the broader Weather Enterprise the ability to rapidly test, develop, and demonstrate AI models for both global and regional ensemble forecasting. This innovative framework is expected to transform the pace of AI research-to-operations transitions, and workshop participants will get an early opportunity to explore the types of AI models that could become operational in the years ahead.

Throughout the workshop, the emphasis will be on empowering the community to innovate quickly using freely available tools and resources. By combining practical instruction with open access to notebooks and datasets, EPIC is helping lower barriers to entry in this field—ensuring that researchers from across the academic, public, and private sectors can contribute to AI advancements in weather prediction.

This course offers a unique opportunity to be at the forefront of the next wave of forecasting innovation. Participants will leave equipped with both the confidence and the tools to experiment with AI applications in their own research, fostering a growing community of scientists advancing the frontiers of predictive science.

_____________________________________________________________________

## The EAGLE Pipeline

To complete this pipeline, see `eagle_pipeline_demo.ipynb`

This notebook walks users through a complete, end-to-end machine learning pipeline for weather prediction. It includes multiple configurations and examples that illustrate each stage of the workflow:

Step 1: Environment setup

Configure the required environments using pip and conda.

Step 2: Training data preparation

Generate training and validation datasets using [ufs2arco](https://ufs2arco.readthedocs.io/en/latest/).

Step 3: Model training

Train a graph-based weather prediction model using [anemoi-core](https://github.com/ecmwf/anemoi-core) packages.

Step 4: Forecast generation

Run inference from a trained model checkpoint using [anemoi-inference](https://anemoi.readthedocs.io/projects/inference/en/latest/).

Step 5: Postprocessing

Process inference with [eagle-tools](https://github.com/NOAA-PSL/eagle-tools) to ensure compatibility with downstream applications.

Step 6: Model verification

Evaluate forecast performance using [wxvx](https://github.com/maddenp-cu/wxvx), comparing predictions against gridded analyses and observations.
