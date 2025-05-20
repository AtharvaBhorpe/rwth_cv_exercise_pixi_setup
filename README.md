A [Pixi](https://pixi.sh/) dev environment setup for my Computer Vision course exercises in RWTH Aachen University.
# Install Pixi
## Linux / MacOS

    curl -fsSL https://pixi.sh/install.sh | sh 

## Windows
    powershell -ExecutionPolicy ByPass -c "irm -useb https://pixi.sh/install.ps1 | iex"

# Clone this repository
    git clone https://github.com/AtharvaBhorpe/rwth_cv_exercise_pixi_setup.git
    cd rwth_cv_exercise_pixi_setup

# Start Jupyter Lab
    pixi run jupyter lab

..and voila! You've created a self-contained environment (using pixi) for computer vision exercises with all dependencies!
