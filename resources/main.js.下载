// JavaScript Document
$(function () {
    /*导航*/
    $(".nav").click(function () {
        if (!$(this).hasClass("active")) {
            $(this).addClass("active");
            $(".navTwo").animate({ "left": "0" }, 200)
            $(".header-bj").show()
        } else {
            $(this).removeClass("active");
            $(".navTwo").animate({ "left": "-200" }, 200)
            $("header-bj").hide()
        }
    })
    $(".header-bj").click(function () {
        $(".nav").removeClass("active");
        $(".navTwo").animate({ "left": "-200" }, 200)
        $(this).hide();
    })
    /*返回顶部*/
    $('.top').click(function () { $('html,body').animate({ scrollTop: '0px' }, 800); return false; });
    $(window).scroll(function () {
        var scrollTop = $(window).scrollTop();
        if (scrollTop > 600) {
            $(".top").show()
        } else {
            $(".top").hide()
        }
    });
    /*手机端导航*/
    $(".enlarge").on("click", function () {
        if ($(this).hasClass("enlargeSelect")) {
            $(this).removeClass("enlargeSelect");
            $(".nav").animate({ "left": "-230px" }, 200);
        } else {
            $(this).addClass("enlargeSelect");
            $(".nav").animate({ "left": "0" }, 200)
        }
    });
    if (window.innerWidth <= 600) {
        $(".public-topNav").hide();
    }
})





