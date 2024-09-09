Just for more information, we are wanting this product page, collection page (quite simple, similar to default Enterprise theme we are using) and two landing pages:



Notes for the product page:
For the scroll in the CHOOSE YOUR SETUP section:

- This section allows the user to add the product and also add multiple cross-sell products at the same time. The cross-sell addon products would be product variants that need to be able to be added into the product metafields, and the title and the image of the addon should be hyperlinked to the product page

- for the addons, I think the best way to do this is to have the following separate metafields on the product page that product variants can be added to: Battery Monitor, Battery Charger, Mounting Bracket, Inverter, Side Rails, RV Compliance Kit, and a discount metafield for each of them where if no value is added there is no discount, however if there is a value it will apply the discount to all addons under that specific metafield

    - > $${\color{yellow}Sathish's}$$ $${\color{yellow}Response/Query}$$      
        - > We will use Metafields and set it to use MetaObjects that will extend the data structure
        
        - > Depending upon the total number of products in the store, there might be a necessity to update (automate) these metafields as an one-time activity, with values (Import feature). We may ignore this if we are not dealing with a lot of products and/or we plan to do this manually

        - > $${\color{yellow}REGARDING}$$ $${\color{yellow}ADDONS}$$
            - > Battery Monitor: I see that we are showing two Battery Monitor product variants in the Figma. I would like to know if we need to allow customization of how many items to display. For instance, assuming we have 10 variants but we choose to show the selected (through metafields) two only or could this run to more than two, four etc.,? The reason I ask this is, depending upon the number of items displayed, the layout needs to be designed accordingly (for both Desktop & Mobile)

            - > Same goes for all other Addons

- This whole section should pause and scroll all the way to the bottom of the right panel before it continues scrolling down the page.

    - > $${\color{yellow}Sathish's}$$ $${\color{yellow}Response/Query}$$
        - > Noted: The feature is called 'Sticky'

- The white bar with the price and the quantity selector should sit at the bottom of the users screen the whole time that they are scrolling through this section. It should show the from $1,849.00 price until the options start being selected, then it should show the total price which is updated when they add more options. The ATC should add the product and any other selected items should be added to the cart

    - > $${\color{yellow}Sathish's}$$ $${\color{yellow}Response/Query}$$
        - > Noted: Sticky ATC

- the stick ATC bar would need to stick on the users screen as they scroll down to the bottom of the page

    - > $${\color{yellow}Sathish's}$$ $${\color{yellow}Response/Query}$$$
        - > Same as above



For the Tech Specs section:
- we will use the default theme 'comparision grid' layout with some CSS changes, but we want to make it allow more than the set 5 (we currently need 8 in one product). We would need product metafields setup as per the figma (the ones down the left side of the grid), and there will need to be a metafield for related products that will pull into this comparison grid, see attached image of the section in customiser from another website doing the same thing we will do.

    - > $${\color{yellow}Sathish's}$$ $${\color{yellow}Response/Query}$$
        - > In my honest opinion, this might not be the ideal thing to do as there is a reason why the theme developers have restricted this to five products. The reason being, we might have to truncate the title, description and a few other elements for each product in order to make it fit the layout (CSS changes). If this is something we cannot live without then I am game. Please check the screenshot I have shared regarding this on how it would look (of course, without much css changes, yet). Allowing of more than five products, technically, should not be a big effort but the CSS changes will be a bit extensive. Just a heads-up!



- [12V Battery Landing Page](https://www.figma.com/proto/yRyiztOwq0MkVjORJGC1nh/CL-Website?node-id=850-231&t=d6yKpCIqU1gsqoPe-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=626%3A51)



- [All Batteries CLP](https://www.figma.com/proto/yRyiztOwq0MkVjORJGC1nh/CL-Website?node-id=749-82&t=FmwuhmB4eN4lCaPT-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=626%3A51)



- We would want the page speed to be above 80 on both desktop and mobile, and not to use add additional apps other than Judge.me for reviews.
    - > $${\color{yellow}Sathish's}$$ $${\color{yellow}Response/Query}$$
        - > Speed Optimization: No false promises as I cannot guarantee 80+ if the theme (demo) itself is not able to show that performance (I have not tested it yet though)



- We have used the Enteprise theme - https://themes.shopify.com/themes/enterprise/styles/digital/preview
    - > $${\color{yellow}Noted}$$
