# Fast AI Experiments

These are experiments created while participating in [Jeremy Howards](https://twitter.com/jeremyphoward)'s absolutely terrific "[Practical Deep Learning for Coders: Part 2](https://itee.uq.edu.au/event/2022/practical-deep-learning-coders-uq-fastai-part-2)" course.

At present, there's only one Jupyter Notebook here, but I'm hoping to add to it as the course progresses.

Here's a listing of what each notebook contains:

* **prompt_editing**: This one has experiments into how to edit elements of an image created using Stable Diffusion by passing the seed used for the original image, the original prompt, and a new edited prompt which contains the changes you want to implement. This is still a WIP since the concept worked  on the first try, but I'm not sure if that's a fluke or not ... Needs more testing.

  | ![original](assets/bicycle-cat.jpg)                          | ![edited](assets/bicycle-dog.jpg)                            |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | **Original prompt:** "a cat riding a bicycle, highly detailed, trending on artstation, colorful" | **Edited prompt:** "a dog riding a bicycle, highly detailed, trending on artstation, colorful" |
  | ![choc-cake](assets/choc-cake.jpg)                           | ![berry-cake](assets/berry-cake.jpg)                         |
  | **Original:** "A chocolate cake, trending on artstation"     | **Edited:** "A strawberry cake, trending on artstation"      |
  | ![forest](assets/forest.jpg)                                 | ![forest-winter](assets/forest-winter.jpg)                   |
  | **Original:** "A fantasy forest, trending on artstation"     | **Edited:** "A fantasy forest in winter, trending on artstation" |
  
  