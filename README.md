# Tableau
Tableau Dashboards
<!-- 
This <script> tag links to the Embedding API library as a JavaScript ES6 module. 
To use the library in your web application, you need to set the type attribute to 
module in the <script> tag. 
-->

<script type="module" src="https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js"></script>

<!-- 
Initialize the API as part of your HTML code by using the <tableau-viz> web component. 
After linking to the API library, the following code is all you need to embed a Tableau view into your HTML pages.
-->

<tableau-viz id="tableauViz"       
  src='[https://public.tableau.com/views/Superstore_24/Overview](https://public.tableau.com/views/ARMS_viz/Main1?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link)'      
  height='600px' width='600px' toolbar='bottom' hide-tabs>
</tableau-viz>



<div class='tableauPlaceholder' id='viz1709947706311' style='position: relative'><noscript><a href='#'><img alt='Main1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;AR&#47;ARMS_viz&#47;Main1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ARMS_viz&#47;Main1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;AR&#47;ARMS_viz&#47;Main1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1709947706311');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='777px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
