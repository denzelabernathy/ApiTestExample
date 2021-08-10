# Running the JSON collection! :star_struck:
This repo serves as a detailed breakdown of how to run my JSON collection that encompasses API requests and tests!

## Using the Postman collection runner (if you already have signed into your existing Postman account)

1. Click the following [link](https://www.postman.com/Denzel-Abernathy-API-Developing-And-Testing/workspace/denzel-abernathy-s-public-postman-workspace-for-api-development-and-testing/collection/17032793-43c32a14-48c5-4796-b802-62cc18bcba5e?ctx=documentation), and you _should_ land on a page that looks like this
	1. ![DenzelAbernathyStepOneConfirmation](https://user-images.githubusercontent.com/35211101/128924224-d0934764-fb65-4b73-8854-10b3f43d708b.png)

2. With your cursor, hover over the `SDET Coding Exercise` collection, then scroll over to the right and click the three ellipses. That action _should_ open the following dropdown menu option list
	1. ![DenzelAbernathyStepTwoConfirmation](https://user-images.githubusercontent.com/35211101/128925327-d4ed879e-1c44-424e-8a40-862c86edf5cc.png)

3. With the ellipses dropdown now present, **click** the `Run collection` option, which will open the `Runner` in a new tab.
	1. ![DenzelAbernathyStepThreeConfirmation](https://user-images.githubusercontent.com/35211101/128927203-b9e325fd-1e82-461e-afae-76f3dbfe8079.png)
	2. This is where you can customize the run to fit any criteria the UI/UX has listed, and once your criteria is finalized simply **click** the `Run SDET Coding Exercise` button

4. Allow several seconds for the runner to send the requests and run the test. Afterwards you _should_ see the following `Results`
	1. ![DenzelAbernathyFinalStepConfirmation](https://user-images.githubusercontent.com/35211101/128927894-ffd2a324-053d-4c21-a6a4-26e4f8d17f7f.png)
	2. Here is where you're able to browse the results from the collection run based off of your criteria selected previously. 
	3. Also you can view if any tests failed, adjust your view to only see the summary of the run, run the collection again, and many other options!


## Using the Newman CLI runner (presuming you're more advanced and understand the basics of CLI/Command Prompts and already have it setup)

#### Installing Newman (tech and OS agnostic)
NodeJS **not** installed | NodeJs installed already
------------ | -------------
Follow this article from [Offical NPM docs](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) | Follow this README.md from [Postman's github](https://github.com/postmanlabs/newman#getting-started)

### After Newman has been installed or is already pre-existing checklist
 
#### Run using JSON file from repo 
- [x] CLI/Command prompt is open and running
- [x] Clone or download repo from [here](https://github.com/denzelabernathy/SDETCodingExercise)
- [x] In your CLI/Command prompt `CD` to where your `sdetCodingExercise.postman_collection.json` file is located 
 
1. Type `newman run sdetCodingExercise.postman_collection.json` in your CLI/Command prompt
2. Click enter on _your_ keyboard

#### Run using public URL link from postman (simplest method after newman is installed)
- [x] CLI/Command prompt is open and running

1. Type newman `run https://www.getpostman.com/collections/75fc3a59abc503bb06f8`

#### Overall your results from either CLI/Command prompt method should look like this
![DenzelAbernathyCliCommandPromptResults](https://user-images.githubusercontent.com/35211101/128937753-ea4aa3f5-ace5-4485-9209-fc28325e0fe8.png)
