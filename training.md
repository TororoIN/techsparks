# Training and Inference Results

## ASR Inference Results



https://user-images.githubusercontent.com/91375589/160338674-b0c39b2a-d294-482d-bee3-4132b7d6d332.mp4

>> कॉफी पीते हैं



https://user-images.githubusercontent.com/91375589/160338693-0adc9052-2cb0-49d8-9d23-e897745f11af.mp4

>> आकाश नीला है
## Translation Inference Results

- Prompt 
> If you want to win, you have to put in efforts
>>  अगर आप जीतना चाहते हैं, तो आपको प्रयास करना होगा

> He had the spirit of the nine tailed fox inside him
>> उनके अंदर नौ पूंछ वाले लोमड़ियों की भावना थी


## Speech Synthesis Inference Results

> He bought all the cake he could

https://user-images.githubusercontent.com/91375589/160335424-2fffb23d-1c49-4b45-8c61-c757b2f2bfcd.mp4


> Mom cooked a delicious meal, along with pudding for dessert

https://user-images.githubusercontent.com/91375589/160335690-27c3e95b-5a32-49b0-a439-b72e8eede965.mp4



## Voice Conversion Inference Results

### Example 1

- Target Speaker

https://user-images.githubusercontent.com/91375589/160333144-a73c5176-6828-4ca6-9ffd-aabe353e6239.mp4

- Source Speaker

https://user-images.githubusercontent.com/91375589/160333261-2bd84bee-b4fa-4c07-8454-16dc6d50c6f8.mp4

- Result 

https://user-images.githubusercontent.com/91375589/160333303-c1e063ef-8200-4f2c-986a-3301e52ad6af.mp4

### Example 2

- Target Speaker


https://user-images.githubusercontent.com/91375589/160333847-9505f317-9a8b-4e76-bb59-d4869fdf9fa2.mp4


- Source Speaker


https://user-images.githubusercontent.com/91375589/160333858-83a8ef7c-dec1-408d-aaaa-9cd36d072215.mp4

- Result 

https://user-images.githubusercontent.com/91375589/160333902-bee119e3-776b-4a1f-8121-f10163c92c9f.mp4



## Some Hiccups...

The Voice Conversion model (AutoVC) performs conversion well only when the data is already seen. So, in true sense, it is not Zero Shot. The zero shot performance of the model is not usable IRL. For this, the user can fine tune the model according to the target speaker's voice when necessary. This can be accomplished using a simple Streamlit UI. 
