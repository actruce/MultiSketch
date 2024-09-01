# MultiSketch

## 1. GIF animations from various sketches
<div>
<p><strong>1. "A basketball player dribbles the ball down low. The ball is bound from top to bottom and bottom to top."</strong></p>
<img src="https://github.com/user-attachments/assets/c4e85ef7-48f0-4509-a362-e073e258ada9" width="600" height="150"/>
<br>
<img src="https://github.com/user-attachments/assets/9cc9e065-974c-4ae0-b19d-68fb993417df" width="250" height="250"/>
</div>
<p></p>

<div>
<p><strong>2. "A butterfly flies to a rose, flaps its wings and flits around, but the rose stays still."</strong></p>
<img src="https://github.com/user-attachments/assets/1046678b-3dac-42d0-9563-1d6f159e166d" width="600" height="150"/>
<br>
<img src="https://github.com/user-attachments/assets/9b557ad0-6920-421f-9ced-b19275ac87d8" width="250" height="250"/>
</div>
<div>

<p><strong>3. "The two dancers are passionately dancing the Cha-Cha, their bodies moving in sync with the infectious Latin rhythm."</strong></p>
<img src="https://github.com/user-attachments/assets/6fcf13e6-b5a6-4fef-bda2-1a7b80ee395c" width="600" height="150"/>
<br>
<img src="https://github.com/user-attachments/assets/5ea94680-f736-4c77-8c3b-2933d1be1260" width="250" height="250"/>
</div>
<div>

<p><strong>4. "Two penguines are shuffling along the ice terrain, taking deliberate and cautious step with its flippers outstretched to maintain balance."</strong></p>
<img src="https://github.com/user-attachments/assets/d3254a7a-d260-42f5-a1bb-186a3ea5fd79" width="600" height="150"/>
<br>
<img src="https://github.com/user-attachments/assets/5164b1ba-5a5d-461d-a34a-55b471270cfc" width="250" height="250"/>
</div>

<div>
<p><strong>5. "The two goldenfishes are gracefully moving through the water, its fins and tail fin gently propelling it forward with effortless agility."</strong></p>
<img src="https://github.com/user-attachments/assets/94786285-25f3-4103-9a09-8fdcfd44d194" width="600" height="150"/>
<br>
<img src="https://github.com/user-attachments/assets/32db58e0-2ef4-4c31-b76f-db66ace02a04" width="250" height="250"/>
</div>

## 2. Comparisons between methods
<p>(a) baseline, Gal et al., Breathing Life Into Sketches Using Text-to-Video Priors, arXiv 2311.13608</p>
<p>(b) Object Separation and three iterative training with SDS loss; object#1 -> object#2 -> combined </p>
<p>(c) Object Separation and three iterative training with SDS loss; object#1 -> object#2 -> combined but without global path </p>
<br><br>

<div>
<p><strong>1. "A basketball player dribbles the ball down low. The ball is bound from top to bottom and bottom to top."</strong></p>
<figure><img src="https://github.com/user-attachments/assets/61ac9f7d-825b-4cea-a8e7-99a23dfefa38" width="200" height="200" border="1"/><figcaption>(a)</figcaption></figure>&nbsp;
<figure><img src="https://github.com/user-attachments/assets/8851d435-d4f9-4ba9-b26d-e22437dbcb4e" width="200" height="200" border="1"/><figcaption>(b)</figcaption></figure>&nbsp;
<figure><img src="https://github.com/user-attachments/assets/9cc9e065-974c-4ae0-b19d-68fb993417df" width="200" height="200" border="1"/><figcaption>(c)</figcaption></figure>
</div>

<div>
<p><strong>2. "A butterfly flies to a rose, flaps its wings and flits around, but the rose stays still."</strong></p>
<figure><img src="https://github.com/user-attachments/assets/c1e4d08d-956f-4784-a811-7c860a544b50" width="200" height="200" border="1"/><figcaption>(a)</figcaption></figure>&nbsp;
<figure><img src="https://github.com/user-attachments/assets/60a1f1c8-376c-49b8-9b50-5fe3b1f3460e" width="200" height="200" border="1"/><figcaption>(b)</figcaption></figure>&nbsp;
<figure><img src="https://github.com/user-attachments/assets/9b557ad0-6920-421f-9ced-b19275ac87d8" width="200" height="200" border="1"/><figcaption>(c)</figcaption></figure>
</div>

<div>
<p><strong>3. "The two dancers are passionately dancing the Cha-Cha, their bodies moving in sync with the infectious Latin rhythm."</strong></p>
<figure><img src="https://github.com/user-attachments/assets/441e4fd8-3b77-4b82-b59a-b4c6c8fb7aba" width="200" height="200" border="1"/><figcaption>(a)</figcaption></figure>&nbsp;
<figure><img src="https://github.com/user-attachments/assets/2a844ceb-e1e9-4969-81b9-eeac0a6e2994" width="200" height="200" border="1"/><figcaption>(b)</figcaption></figure>&nbsp;
<figure><img src="https://github.com/user-attachments/assets/5ea94680-f736-4c77-8c3b-2933d1be1260" width="200" height="200" border="1"/><figcaption>(c)</figcaption></figure>
</div>

<div>
<p><strong>4. "Two penguines are shuffling along the ice terrain, taking deliberate and cautious step with its flippers outstretched to maintain balance."</strong></p>
<figure><img src="https://github.com/user-attachments/assets/09be971f-d479-4b54-9019-1997240206ec" width="200" height="200" border="1"/><figcaption>(a)</figcaption></figure>&nbsp;
<figure><img src="https://github.com/user-attachments/assets/8cffdce6-8288-4be4-988c-1732af683ee8" width="200" height="200" border="1"/><figcaption>(b)</figcaption></figure>&nbsp;
<figure><img src="https://github.com/user-attachments/assets/5164b1ba-5a5d-461d-a34a-55b471270cfc" width="200" height="200" border="1"/><figcaption>(c)</figcaption></figure>
</div>

## 3. Failure Cases
<div>
<p><strong>1. "A soccer player kicks a soccer ball as hard as he can to take a shot. The ball moves forward, and the kicking foot moves from back to front."</strong></p>
<img src="https://github.com/user-attachments/assets/2501e1d6-4c36-47b8-be4f-fb0ec6cd4e20" width="150" height="150"/>&nbsp;
<img src="https://github.com/user-attachments/assets/3a9ceafd-fe1e-4d26-9f11-253b06a603a0" width="150" height="150"/>
<br>
<p><strong> A sample video generated from pre-trained text-to-video diffusion model (<a href="https://arxiv.org/abs/2308.06571">Model Scope</a>) shows lack of fisibility about training. </strong></p>
<a href=""></a>
</div>


<div>
<p><strong>2. "On a horizontal stretch of road, two cars are driving toward each other in their respective lanes."</strong></p>
<img src="https://github.com/user-attachments/assets/d7bc86c1-6d9b-4a2d-89a5-a52cb2f4315f" width="150" height="150"/>&nbsp;
<img src="https://github.com/user-attachments/assets/4cca1215-395a-490e-8d0b-e0abed082fad" width="150" height="150"/>
<br>
<p><strong> A sample video generated from pre-trained text-to-video diffusion model (<a href="https://arxiv.org/abs/2308.06571">Model Scope</a>) shows lack of fisibility about training. </strong></p>
<a href=""></a>
</div>
