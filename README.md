# Pinkdream
/*
@plugin
@name Pinkdream
@version 1.0
@author UsefulAngel
@description Missing.
@endplugin
*/

(function(){
let documentWidth = $("body").width(),
    contentWidth = $(".gsWrap").width(),
    availableSide = (documentWidth - contentWidth)/2;
  
/*** Main ***/
$("body").prepend('<strip1 style="background-color: #FFC0CB; position: fixed; z-index: 0; width: 5px; height: 100%;"></strip1>');
$("body").prepend('<strip2 style=" background-color: #FFC0CB; position: fixed; z-index: 0; width: 5px; height: 100%;"></strip2>');
$("strip1").css("left", availableSide-20);
$("strip2").css("right", availableSide-20);
$("body").css("color", "#061d3f");
$("body").append('<style>footer{ position: relative; z-index: 1}</style>');
  
//.titleBar
$(".titleBar").css("background-color", "rgba(255,192,203)");
$(".titleBar").css("border", "1px solid rgba(255,114,118)");
$(".titleBar").css("box-shadow", "0 8 32px rgb(255,192,203)");

//.titleBar2
$(".titleBar2").css("background-color", "rgba(255,192,203)");
$(".titleBar2").css("border", "1px solid rgba(255,114,118)");
$(".titleBar2").css("box-shadow", "0 8 32px rgb(255,192,203)");

//.titleBar3
$(".titleBar3").css("background-color", "rgba(255,192,203)");
$(".titleBar3").css("border", "1px solid rgba(255,114,118)");
$(".titleBar3").css("box-shadow", "0 8 32px rgb(255,192,203)");

//.itemChipHead
$(".itemChipHead").css("background-color", "rgba(255,192,203)");
$(".itemChipHead").css("border", "1px solid rgba(255,114,118)");
$(".itemChipHead").css("box-shadow", "0 8 32px rgb(255,192,203)");

// Price Stable & Price Source
$(".greenRow").css("background-color", "#FFC0CB");
$(".greenRow").css("color", "#FFF");

// Price Unstable
$(".redRow").css("background-color", "#FF0000");
$(".redRow").css("color", "#FFF");

// Price Editor
$(".blueRow").css("background-color", "#ffcccb");
$(".blueRow").css("color", "FF0000");

//.floatButton
$(".floatButton").css("background-color", "FFC0CB");
$(".floatButton").css("border", "4px solid "FF0000");
$(".floatButton").css("border-radius", "8px");
$(".floatButton").css("width", "48.5%");

//.floatButton2
$(".floatButton2").css("background-color", "rgba(255,114,118)");
$(".floatButton2").css("border", "3px rgba (255,114,118)");
$(".floatButton2").css("border-radius", "5px");
$(".floatButton2").css("width", "50%");

// Marketplace (Offer)
$(".floatButton.findOffer").css("background-color", "transparent");
$(".floatButton.findOffer").css("border", "2px solid #e7b55c");
$(".floatButton.findOffer").css("border-radius", "8px");
$(".floatButton.findOffer").css("width", "calc(100% - 10px)");

// Marketplace (BUY)
$(".floatButton.boughtBtn.buyBtn").css("background-color", "transparent");
$(".floatButton.boughtBtn.buyBtn").css("border", "2px solid #e7b55c");
$(".floatButton.boughtBtn.buyBtn").css("border-radius", "8px");
$(".floatButton.boughtBtn.buyBtn").css("width", "calc(100% - 10px)");

// Marketplace (SELL)
$(".floatButton.soldBtn.sellBtn").css("background-color", "transparent");
$(".floatButton.soldBtn.sellBtn").css("border", "2px solid #e7b55c");
$(".floatButton.soldBtn.sellBtn").css("border-radius", "8px");
$(".floatButton.soldBtn.sellBtn").css("width", "calc(100% - 10px)");

/** Sidebar **/
$(".header").css("color", "	#FFB6C1");
$(".table").css("background-color", "transparent");
$(".odd").css("background-color", "transparent");
$(".user-info").css("background", "url(https://cdn.discordapp.com/attachments/716165570264956929/835449011468894238/unknown.png)");
$(".title").css("color", "#FFB6C1");
$(".profile-header").css("border-radius", "5px 5px 0px 0px");

/* Staff */
$(".userAvatar").css("border-radius", "50%");
$(".card.bg-orng").css("border-radius", "60px 0px 0px 60px");
$(".card.bg-orng").css("background-color", "rgba(255,192,203)");
$(".card.bg-lOrng").css("border-radius", "60px 0px 0px 60px");
$(".card.bg-lOrng").css("background-color", "rgba(255,192,203)");
$(".card.bg-lBlue").css("border-radius", "60px 0px 0px 60px");
$(".card.bg-lBlue").css("background-color", "rgba(0,132,235,.5)");
})();
