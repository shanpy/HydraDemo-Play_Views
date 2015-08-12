This project is a clone of <a href="https://github.com/projecthydra/hydra/wiki/Dive-into-Hydra">Dive into Hydra</a> demo tutorial project. I have finished tutorial steps and now I want to use it as a platform of my experiments.

###8/11/15

After play with Hydra demo project and looking into lots of supplemental documents, I think it's time now to jump to code and play with it.

I decided to start from playing with views, because of following reason:

- I can have same experience as a end user, which can help me to improve future end user experience.

- I can touch data without risking of mess it up unexpectedly, while I can still learn the process of the data processing on back-end, by reading messages from rails server console. *It's not bad to mess project up as a beginner :) but due to time limitation, I want to choose safest way.*

- I can learn the interaction between view and controller.

- Personal reason: Currently I'm more familiar with front-end(HTML/CSS/JavaScript) comparing to Ruby. Jumping from front-end can push me to touch Ruby code in a reasonable way (instead of throw everything in one time), and guide me to explore the login process of Ruby code working in Hydra. In this way, I can not only learn the logic of Hydra, but also being familiar with RoR.

**Process**

I replace the old view folder of hydra-demo project by this folder `/home/pengyin/.rvm/gems/ruby-2.2.2/gems/blacklight-5.13.1/app/views`. You should change address based your ruby gem setting. All `erb` files in new view folder are views for hydra-demo project. I'm free to modify it and see results from rails server.