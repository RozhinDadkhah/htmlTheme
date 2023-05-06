$(document).ready(function () {
    // $(".icon").click(function (e) {
    //     $("div").addClass("show")
    // });

    $(".close").click(function (e) {
        $(".offcanvas").removeClass("show")
    });

    $(function () {
        $('#demo').counto(63);
    });

    $(function () {
        $('#demo').counto(63, 10000);
    });

    $(function () {
        $('#demo2').counto(99);
    });

    $(function () {
        $('#demo2').counto(99, 10000);
    });

    $(function () {
        $('#demo3').counto(3958);
    });

    $(function () {
        $('#demo3').counto(3958, 10000);
    });




    $(window).scroll(function () {
        if (window.pageYOffset > 80) {
            $("header").css("background-color", "#232628");
        } else {
            $("header").css("background-color", "transparent");
        }
    });

    $(".wow").each(function () {
        var wowHeight = $(this).height();
        $(this).attr("data-wow-offset", wowHeight);
    });
});
