In this project let's build a IPL Dashboard App by applying the basic concepts.

The IPL logo in the Home Route should have the HTML alt attribute value as ipl-logo

The API response received from the given apiUrl should be converted to camel case

Wrap the Loader component with an HTML container element and add the testid attribute value as loader to it as shown below

<div testid="loader">
     <Loader type="Oval" color="#ffffff" height={80} width={80} />
</div>
Render HomeRoute component when path in URL matches /

Render TeamMatchesRoute component when path in URL matches /team-matches/:id

No need to use the BrowserRouter in App.js as we have already included in index.js file

Each TeamMatchesRoute should have different gradient colors as background based on the selected team


All components you implement should go in the src/components directory.
