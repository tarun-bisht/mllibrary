# mlLibrary
 
- mlLibrary is collection of trained machine learning models for web apps. 
- All models are compatible with tensorflow-js.
- Models are hosted using firebase hosting.

visit [models-lib.web.app](https://models-lib.web.app/) for list of models currently avaliable.

## Steps to deploy your own model library

- Create a firebase project at [firebase console](https://console.firebase.google.com/)
- Install firebase cli using nodejs or executable. [Steps here](https://firebase.google.com/docs/cli)
- Move inside a direcotry and create a firebase project using firebase hosting project using `firebase init`
- Read and follow steps from cli
- A public folder will be created with `index.html` inside it.
- Create your template for model library with `html` and `css`
- Create a model's folder and organise your models inside that folder
- Link all model's json path to `index.html` for easy accessing
- Enable CORS for `.json` and `.bin` file.
- Deploy project with `firebase deploy`

## Contribution
Anyone can contribute by providing trained models converted into tfjs format. For more info contact [here](https://tarunbisht.com/contact) or E-mail to contact@tarunbisht.com 

