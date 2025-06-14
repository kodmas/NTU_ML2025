# Machine Learning 2025 HW10

**Student**: b09901142 呂睿超

## Environment
* This assignment is done on Colab
* Computing device: T4 * 1
  
## Reproduce hyperparameters settings
* Since I did this assignment separately for the 6 objects, I will provide the detail settings below. If TAs need 6 separate files for reproduce, please contact me and I'll response promptly. (email: b09901142@ntu.edu.tw)
* Except Object 6, I only modified the listed hyperparameters and didn't modify any code other than these.
  
* Object 1 (Custom Diffusion)
  * training
    * lr = 7.5e-6
    * steps 1200
    * parameters: crossattn
  * inference
    * inference step: 100
    * guidance_scale = 7.5
  
* Object 2 (BLIP)
  * inference
    * inference step: 100
    * guidance_scale = 7.5
  
* Object 3 (Custom Diffusion)
  * training
    * lr = 7.5e-6
    * steps 1200
    * parameters: crossattn
  * inference
    * inference step: 80
    * guidance_scale = 4.0

* Object 4 (Custom Diffusion)
  * training
    * lr = 7.5e-6
    * steps 1200
    * parameters: crossattn_kv
  * inference
    * inference step: 250
    * guidance_scale = 7.5

* Object 5 (Custom Diffusion)
  * training
    * lr = 6e-6
    * steps 1500
    * parameters: crossattn
  * inference
    * inference step: 150
    * guidance_scale = 7.5

* Object 6 (Custom Diffusion)
  * training
    * lr = 6e-6
    * steps 1500
    * parameters: crossattn
  * inference
    * inference step: 200
    * guidance_scale = 7.0
  * **Note**: I generated object-6 under specific transfomer version **4.50.3** using the following
    * `pip install transformer==4.50.3`


## References
* Gemini 2.5 flash for instance prompt
  * [Chat History Link](https://g.co/gemini/share/24a556ba3687)

