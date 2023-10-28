1. add this link in your header
  <script src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>


2. attach file language.js in header if you need customization


3.  give follwoing id to your element
  
  <i id="google_translate_element" style="color: black;" class="fa fa-language fa-xl" onclick="foo();"></i>




4. css for link customization if required

.goog-te-gadget img{
	display: none !important;
}

.VIpgJd-ZVi9od-l4eHX-hSRGPd, .VIpgJd-ZVi9od-l4eHX-hSRGPd:link, .VIpgJd-ZVi9od-l4eHX-hSRGPd:visited, .VIpgJd-ZVi9od-l4eHX-hSRGPd:hover, .VIpgJd-ZVi9od-l4eHX-hSRGPd:active{
	display: none !important;
}

.goog-te-gadget .goog-te-combo{
	border: none!important;
    background: transparent!important;
	margin: 4px 0px 0px 7px !important;
}
.goog-te-gadget select{
	width: 20px !important;
}

.goog-logo-link {
    display:none !important;
} 
    
.goog-te-gadget{
    color: transparent !important;
}

.VIpgJd-ZVi9od-ORHb-OEVmcd {
display: none;

}

.goog-te-banner-frame.skiptranslate {
    display: none !important;
    } 
    
    body {
		top: 0px !important; 
		}
	






// if you want to change language on click use follwoing
//window.location ='#googtrans(ar|en)';location.reload();


// if you want to change languages on click dynamic or manually use follwoing you can update as per your needs

// function foo(ele) {
//   var text = ele.textContent;
//   var firstlang, secondlang, newtext;

//   if(text == 'English' || text == 'إنجليزيالعربيةالإنجليزيةتدعمه' || text == 'Englishالعربيةالإنجليزيةتدعمه'){
//   firstlang = 'ar';
//     secondlang = 'en';
//     newtext = 'عربى';
//   }if (text === 'عربى') {
//     firstlang = 'en';
//     secondlang = 'ar';
//     newtext = 'English';
//   }

//     window.location = '#googtrans(' + firstlang + '|' + secondlang + ')';
//     location.reload();


// }



