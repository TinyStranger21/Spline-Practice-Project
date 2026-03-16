# Spline-Practice-Project
To familirize myself with Spline, I made an interactive eye ball that blinks every 3 seconds, tracks a block of interactive text, and turns red when irritated.

## Planning

Honestly not a lot went into this phase because the eyeball came to me after I remembered I could make a 3D model track my mouse. The only thing that came to my mind was a spooky eyeball. I do a lot of 3D modeling, mainly in a way that incorporates actaul measurements, so this project didn't have the same sketching and prototyping because it was only gonna be in the digital realm and not 3D printed.

## Execution

First here are the tutorials that I loosely followed to help me with this project:

https://youtu.be/_3ETQW_C6s0?si=UhznO-eDmQUTRXZf

https://youtu.be/i29GQQUxtl0?si=aF64-LIO0SKmYq8M

https://youtu.be/L4fD9X_uhtc?si=eiXGO_ICV2tNoRbi

### Modeling the Eye 

Yes I did look at an image of an eye for small amount of reference, I completly forgot what the pupil looked like. I started by creating a sphere, then extruding the sides of the sphere so its kinda resembles a football. From here I starting making the iris (outer ring) from a sphere that I turned into more of a frissbee and then cut the body of the iris with a copy of the eyeball. This made sure the iris stayed flush with the eyeball, I bet there is a better way.

For the pupil, I kept this as a sphere because I wanted to have more of a 3D effect but this proved to be kinda a issue with the interaction part of this model, as it was extruded from the eyeball.

My favorite part was making the eye lids. In order to do this, I made a copy of the eyeball shape, scaled it a good amount, and then used the pen tool to create the shape of a persons eye lid opening to I could cut that shape out of the upscaled eyeball copy. This in the end made a full eyelid that would cover every part of the eye excpet the pupil and iris area. The surprising part about this was when I changed the scale of the Y axis, it would make the eyelid close, while not affecting every other part of the eyelid model.

### Adding Interaction

#### Mouse Tracking

I had a lot more trouble with the interaction bits than the 3D modeling. I don't know if Spline was being wonky or if there was something I was missing but I could not get the base state and the state to be different. After a few refreshes and some research, I got it to work. 

The first interaction I started with was the mouse tracking, this was very easy and only takes a few clicks to get. After playing with it a little, it felt a little empty. I decided to create the word "Here" in a sketchy font and make that the object for the eyeball to track. I had to make a few more interaction because the "Here" object need the ability to be clicked and dragged while also controlling the direction of the eyeball. I also was able to change the speed and distance the eye could track the object on screen. This allowed me to make the movement a lot more smooth and eerie.

<img width="3456" height="1982" alt="image" src="https://github.com/user-attachments/assets/474fb3f3-bd45-405e-8216-c8c289d83182" />

Tutorial:
https://youtu.be/L4fD9X_uhtc?si=eiXGO_ICV2tNoRbi

#### Blinking

After learning that changing the scale of the eyelids on the Y axis would create a blinking motion, I decided I wanted this to be another interaction. Originally, I made this on click or button press, but this made the user have to hold the button or click in order to make the eye do the full motion. I move from a interaction to making it automated. I added a start event that would make the eyelids transition from base state to state every 3 seconds. I also added a pingpong cycle so that it would close and open the eyelids in the same motion. This made the animation a lot easier and more lifelike because you didn't have to control the blinking

<img width="3456" height="1982" alt="image" src="https://github.com/user-attachments/assets/17411a3c-f3cb-49c6-8239-941bfc913fec" />

Tutorial:
https://youtu.be/_3ETQW_C6s0?si=UhznO-eDmQUTRXZf

#### Foggy Introduction

I wanted to implement some kind of introduction for the eye ball instead of it just being on screen. Ive played with fog a little bit but never really understood what it did in spline. After watching a tutorial and testing it out, I implemented a base start and start state that happen when the project is played. The eye slowly emerges from the fog and slowly starts tracking the "Here" object. The fog makes it possible to dissapear and appear on the screen with an ominous feel, really adding to the overall project.

<img width="3456" height="1982" alt="image" src="https://github.com/user-attachments/assets/1be543e7-e2fd-4462-93cc-ec02022dad96" />

Tutorial:
https://youtu.be/i29GQQUxtl0?si=aF64-LIO0SKmYq8M

## Conclusion

Overall, I love Spline and I am very exicted to learn how to implement more into my models. 3D modeling has always been a passion of mine but I never got far enough to get interactivity into my projects. I am excited to implement 3D interactions into my future websites and projects.
