


<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta name="viewport" content="width=device-width">
    <meta name="MobileOptimized" content="320">
    <title>...</title>
    <style type="text/css">
        body, p, input, h1, h2, h3, h4, h5, h6, ul, li, dl, dt, dd, form {
            margin: 0;
            padding: 0;
            list-style: none;
            vertical-align: middle;
        }

        h1, h2, h3, h4, h5, h6, strong, em {
            font-weight: normal;
            font-style: normal;
        }

        body {
            font-family: "\5FAE\8F6F\96C5\9ED1", Helvetica;
            color: #000;
            background-color: #fff;
            -webkit-text-size-adjust: none;
            font-size: 16px;
        }

        header, section, footer, img {
            display: block;
            margin: 0;
            padding: 0;
        }

        img {
            border: 0;
        }

        a {
            text-decoration: none;
            color: #1064b2;
        }

        .longwb_box {
            min-width: 320px;
            overflow: hidden;
        }

        .longwb_box img {
            max-width: 100%
        }

        .longwb_box_hd {
            min-height: 65px;
            position: relative;
            border-bottom: 2px solid #D9D9D9;
        }

        .user_block {
            overflow: hidden;
            padding: 7px 10px 10px 10px;
            display: -webkit-box;
        }

        .user_block .avatar {
            display: inline-block;
            margin-top: 3px;
            margin-right: 10px;
        }

        .user_block .cnt {
            -webkit-box-flex: 1;
            overflow: hidden;
        }

        .user_block .avatar img {
            width: 40px;
            height: 40px;
        }

        .user_block .tx_id {
            display: block;
            color: #999;
            font-size: 12px;
        }

        .longwb_box_hd .longwb_sign {
            display: block;
            width: 86px;
            height: 21px;
            position: absolute;
            right: 10px;
            top: 22px;
            text-indent: -9999px;
            background: url(http://mat1.gtimg.com/www/mb/img/p1/longwb_page_3.png) no-repeat;
        }

        .longwb_box_hd .bt_line {
            display: block;
            width: 60px;
            height: 8px;
            position: absolute;
            bottom: -2px;
            left: -6px;
            background: url(http://mat1.gtimg.com/www/mb/img/p1/longwb_page_1.png) no-repeat;
        }

        .longwb_box_bd {
            padding: 10px 0;
        }

        .longwb_title {
            color: #000;
            font-size: 20px;
            font-weight: 700;
            margin-bottom: 10px;
        }

    </style>
    <style type="text/css" adt="123"></style>
    <script>!
        function e(t, n, i) {
            function o(a, s) {
                if (!n[a]) {
                    if (!t[a]) {
                        var l = "function" == typeof require && require;
                        if (!s && l) return l(a, !0);
                        if (r) return r(a, !0);
                        var c = new Error("Cannot find module '" + a + "'");
                        throw c.code = "MODULE_NOT_FOUND",
                            c
                    }
                    var d = n[a] = {
                        exports: {}
                    };
                    t[a][0].call(d.exports, function (e) {
                        var n = t[a][1][e];
                        return o(n ? n : e)
                    }, d, d.exports, e, t, n, i)
                }
                return n[a].exports
            }

            for (var r = "function" == typeof require && require, a = 0; a < i.length; a++) o(i[a]);
            return o
        }({
            1: [function (e) {
                var t = window.location.href,
                    n = document.createElement("div"),
                    i = document.createElement("i");
                if (i.setAttribute("id", "ADT-PlayHTML5-btn"), i.innerText = "HTML5\u89c6\u9891", i.setAttribute("style", "display:inline-block;font-size: 20px;padding:5px 10px;font-weight: 700;line-height:34px;color: #fff;text-align: center;vertical-align: baseline;border-radius:10px;background-color: #428bca;cursor: pointer;font-style: normal;"), n.setAttribute("style", "float:right;margin-top:-50px;width:300px;height:50px;padding-top:8px;"), n.appendChild(i), /v\.youku\.com\/v_show\/.*/.test(t)) document.querySelector(".s_main div.base").appendChild(n);
                else if (/www\.tudou\.com\/(albumplay|programs)\/.*/.test(t)) document.querySelector("#summary").appendChild(n);
                else if (/www\.mgtv\.com\/v\/.*/.test(t)) {
                    var i = document.createElement("i"),
                        o = document.createElement("div"),
                        r = document.createElement("em");
                    i.setAttribute("style", "display:inline-block;margin:auto 20px;cursor:pointer;"),
                        i.innerText = "HTML5\u89c6\u9891",
                        r.innerText = "|",
                        r.setAttribute("class", "v-panel-dividing"),
                        o.setAttribute("style", "margin-right: 10px;height: 28px;overflow: hidden;position: relative;top: -1px;float: left;"),
                        o.appendChild(r),
                        o.appendChild(i),
                        document.querySelector("div.v-panel-box").appendChild(o)
                }
                i.addEventListener("click", function () {
                    function t(e, t) {
                        if (!e) return console.log("\u89e3\u6790\u5185\u5bb9\u5730\u5740\u5931\u8d25"),
                            void delete window[s];
                        console.log("\u89e3\u6790\u5185\u5bb9\u5730\u5740\u5b8c\u6210" + e.map(function (e) {
                                return '<a href="' + e[1] + '" target="_blank">' + e[0] + "</a>"
                            }).join(" "));
                        var n = o("div", {
                            appendTo: document.body,
                            style: {
                                position: "fixed",
                                background: "rgba(0,0,0,0.8)",
                                top: "0",
                                left: "0",
                                width: "100%",
                                height: "100%",
                                zIndex: "999999"
                            }
                        });
                        o("div", {
                            appendTo: n,
                            style: {
                                width: "1120px",
                                height: "630px",
                                position: "absolute",
                                top: "40%",
                                left: "50%",
                                marginTop: "-250px",
                                marginLeft: "-560px",
                                borderRadius: "2px",
                                boxShadow: "0 0 2px #000000, 0 0 200px #000000"
                            }
                        }),
                            o("div", {
                                appendTo: n,
                                style: {
                                    position: "absolute",
                                    bottom: "10px",
                                    left: "0",
                                    right: "0",
                                    height: "20px",
                                    lineHeight: "20px",
                                    textAlign: "center",
                                    fontSize: "12px",
                                    fontFamily: "arial, sans-serif"
                                }
                            });
                        var a = o("div", {
                            appendTo: n,
                            innerHTML: '<div id="html5_Player_placeHolder"></div>',
                            style: {
                                width: "1120px",
                                height: "630px",
                                position: "absolute",
                                backgroundColor: "#000000",
                                top: "40%",
                                left: "50%",
                                marginTop: "-250px",
                                marginLeft: "-560px",
                                borderRadius: "2px",
                                overflow: "hidden"
                            }
                        });
                        o("div", {
                            appendTo: a,
                            innerHTML: "&times;",
                            style: {
                                width: "20px",
                                height: "20px",
                                lineHeight: "20px",
                                textAlign: "center",
                                position: "absolute",
                                color: "#ffffff",
                                fontSize: "20px",
                                top: "5px",
                                right: "5px",
                                textShadow: "0 0 2px #000000",
                                fontWeight: "bold",
                                fontFamily: 'Garamond, "Apple Garamond"',
                                cursor: "pointer"
                            }
                        }).onclick = function () {
                            document.body.removeChild(n),
                                l.video.src = "about:blank",
                                delete window[s]
                        };
                        var l = new r("html5_Player_placeHolder", "1120x630", e, t);
                        l.iframe.contentWindow.focus(),
                            i(),
                            l.iframe.style.display = "block",
                            window[s] = !0
                    }

                    var n, i = e("./flashBlocker"),
                        o = e("./createElement"),
                        r = e("./player"),
                        a = e("./purl"),
                        s = e("./h5key"),
                        l = e("./seekers");
                    if (1 != window[s]) {
                        var c = a(location.href);
                        "zythum.sinaapp.com" === c.attr("host") && "/mama2/ps4/" === c.attr("directory") && c.param("url") && (c = a(c.param("url"))),
                            l.forEach(function (e) {
                                n !== !0 && !!e.match(c) == !0 && (console.log("\u5f00\u59cb\u89e3\u6790\u5185\u5bb9\u5730\u5740"), n = !0, e.getVideos(c, t))
                            }),
                        void 0 === n && console.log("\u627e\u4e0d\u5230\u89e3\u6790")
                    }
                })
            },
                {
                    "./createElement": 4,
                    "./flashBlocker": 5,
                    "./h5key": 6,
                    "./player": 9,
                    "./purl": 10,
                    "./seekers": 15
                }],
            2: [function (e, t) {
                function n(e, t) {
                    return void 0 === e ? t : e
                }

                function i(e, t) {
                    return 0 === t.length ? e : e + (-1 === e.indexOf("?") ? "?" : "&") + t
                }

                function o(e) {
                    var t = n(e.url, ""),
                        o = s(n(e.param, {})),
                        l = n(e.method, "GET"),
                        c = n(e.callback, a),
                        d = n(e.contentType, "json"),
                        u = n(e.context, null);
                    if (e.jsonp) return r(i(t, o), c.bind(u), "string" == typeof e.jsonp ? e.jsonp : void 0);
                    var h = new XMLHttpRequest;
                    "get" === l.toLowerCase() && (t = i(t, o), o = ""),
                        h.open(l, t, !0),
                        h.setRequestHeader("Content-Type", "application/x-www-form-urlencoded; charset=UTF-8"),
                        h.send(o),
                        h.onreadystatechange = function () {
                            if (4 === h.readyState) {
                                if (200 === h.status) {
                                    var e = h.responseText;
                                    if ("json" === d.toLowerCase()) try {
                                        e = JSON.parse(e)
                                    } catch (t) {
                                        e = -1
                                    }
                                    return c.call(u, e)
                                }
                                return c.call(u, -1)
                            }
                        }
                }

                var r = e("./jsonp"),
                    a = e("./noop"),
                    s = e("./queryString");
                t.exports = o
            },
                {
                    "./jsonp": 7,
                    "./noop": 8,
                    "./queryString": 11
                }],
            3: [function (e, t) {
                t.exports = !!document.createElement("video").canPlayType("application/x-mpegURL")
            },
                {}],
            4: [function (e, t) {
                function n(e, t) {
                    var n = document.createElement(e);
                    if ("function" == typeof t) t.call(n);
                    else for (var i in t) if (t.hasOwnProperty(i)) switch (i) {
                        case "appendTo":
                            t[i].appendChild(n);
                            break;
                        case "innerHTML":
                        case "className":
                        case "id":
                            n[i] = t[i];
                            break;
                        case "style":
                            var o = t[i];
                            for (var r in o) o.hasOwnProperty(r) && (n.style[r] = o[r]);
                            break;
                        default:
                            n.setAttribute(i, t[i] + "")
                    }
                    return n
                }

                t.exports = n
            },
                {}],
            5: [function (e, t) {
                var n = '<div style="text-shadow:0 0 2px #eee;letter-spacing:-1px;background:#eee;font-weight:bold;padding:0;font-family:arial,sans-serif;font-size:30px;color:#ccc;width:152px;height:52px;border:4px solid #ccc;border-radius:12px;position:absolute;top:50%;left:50%;margin:-30px 0 0 -80px;text-align:center;line-height:52px;">Flash</div>',
                    i = 0,
                    o = {},
                    r = function () {
                        var e = this.getAttribute("data-flash-index"),
                            t = o[e];
                        t.setAttribute("data-flash-show", "isshow"),
                            this.parentNode.insertBefore(t, this),
                            this.parentNode.removeChild(this),
                            this.removeEventListener("click", r, !1)
                    },
                    a = function (e, t, a) {
                        var s = i++,
                            l = document.defaultView.getComputedStyle(e, null),
                            c = l.position;
                        c = "static" === c ? "relative" : c;
                        var d = l.margin,
                            u = "inline" == l.display ? "inline-block" : l.display,
                            l = ["", "width:" + t + "px", "height:" + a + "px", "position:" + c, "margin:" + d, "display:" + u, "margin:0", "padding:0", "border:0", "border-radius:1px", "cursor:pointer", "background:-webkit-linear-gradient(top, rgba(240,240,240,1)0%,rgba(220,220,220,1)100%)", ""];
                        o[s] = e;
                        var h = document.createElement("div");
                        return h.setAttribute("title", "&#x70B9;&#x6211;&#x8FD8;&#x539F;Flash"),
                            h.setAttribute("data-flash-index", "" + s),
                            e.parentNode.insertBefore(h, e),
                            e.parentNode.removeChild(e),
                            h.addEventListener("click", r, !1),
                            h.style.cssText += l.join(";"),
                            h.innerHTML = n,
                            h
                    },
                    s = function (e) {
                        if (e instanceof HTMLObjectElement) {
                            if ("" == e.innerHTML.trim()) return;
                            if (e.getAttribute("classid") && !/^java:/.test(e.getAttribute("classid"))) return
                        } else if (!(e instanceof HTMLEmbedElement)) return;
                        var t = e.offsetWidth,
                            n = e.offsetHeight;
                        t > 160 && n > 60 && a(e, t, n)
                    };
                t.exports = function () {
                    for (var e = document.getElementsByTagName("embed"), t = document.getElementsByTagName("object"), n = 0, i = t.length; i > n; n++) t[n] && s(t[n]);
                    for (var n = 0, i = e.length; i > n; n++) e[n] && s(e[n])
                }
            },
                {}],
            6: [function (e, t) {
                t.exports = "html5playerforadblockyouknowwhatimean"
            },
                {}],
            7: [function (e, t) {
                function n() {
                    return a + s++
                }

                function i(e, t, i) {
                    i = i || "callback";
                    var a = n();
                    window[a] = function (e) {
                        clearTimeout(s),
                            window[a] = r,
                            t(e),
                            document.body.removeChild(c)
                    };
                    var s = setTimeout(function () {
                            window[a](-1)
                        }, l),
                        c = o("script", {
                            appendTo: document.body,
                            src: e + (e.indexOf("?") >= 0 ? "&" : "?") + i + "=" + a
                        })
                }

                var o = e("./createElement"),
                    r = e("./noop"),
                    a = "MAMA2_HTTP_JSONP_CALLBACK",
                    s = 0,
                    l = 1e4;
                t.exports = i
            },
                {
                    "./createElement": 4,
                    "./noop": 8
                }],
            8: [function (e, t) {
                t.exports = function () {
                }
            },
                {}],
            9: [function (e, t) {
                var n;
                !
                    function i(t, n, o) {
                        function r(s, l) {
                            if (!n[s]) {
                                if (!t[s]) {
                                    var c = "function" == typeof e && e;
                                    if (!l && c) return c(s, !0);
                                    if (a) return a(s, !0);
                                    throw new Error("Cannot find module '" + s + "'")
                                }
                                var d = n[s] = {
                                    exports: {}
                                };
                                t[s][0].call(d.exports, function (e) {
                                    var n = t[s][1][e];
                                    return r(n ? n : e)
                                }, d, d.exports, i, t, n, o)
                            }
                            return n[s].exports
                        }

                        for (var a = "function" == typeof e && e, s = 0; s < o.length; s++) r(o[s]);
                        return r
                    }({
                        1: [function (e, t) {
                            function n(e) {
                                for (var t = [], n = 1; n < arguments.length; n++) {
                                    var o = arguments[n],
                                        r = o.init;
                                    t.push(r),
                                        delete o.init,
                                        i(e.prototype, o)
                                }
                                e.prototype.init = function () {
                                    t.forEach(function (e) {
                                        e.call(this)
                                    }.bind(this))
                                }
                            }

                            var i = e("./extend");
                            t.exports = n
                        },
                            {
                                "./extend": 9
                            }],
                        2: [function (e, t) {
                            var n = e("./player.css"),
                                i = e("./player.html"),
                                o = (e("./extend"), e("./createElement")),
                                r = e("./parseDOMByClassNames");
                            t.exports = {
                                init: function () {
                                    var e = function () {
                                            var e = this.iframe.contentDocument.getElementsByTagName("head")[0],
                                                t = this.iframe.contentDocument.body;
                                            o("style", function () {
                                                e.appendChild(this);
                                                try {
                                                    this.styleSheet.cssText = n
                                                } catch (t) {
                                                    this.appendChild(document.createTextNode(n))
                                                }
                                            }),
                                                o("link", {
                                                    appendTo: e,
                                                    href: "http://libs.cncdn.cn/font-awesome/4.3.0/css/font-awesome.min.css",
                                                    rel: "stylesheet",
                                                    type: "text/css"
                                                }),
                                                t.innerHTML = i,
                                                this.DOMs = r(t, ["player", "video", "video-frame", "comments", "comments-btn", "play", "progress_anchor", "buffered_anchor", "fullscreen", "allscreen", "hd", "volume_anchor", "current", "duration"]),
                                                this.video = this.DOMs.video
                                        }.bind(this),
                                        t = document.getElementById(this.id),
                                        a = this.iframe = o("iframe", {
                                            allowTransparency: !0,
                                            frameBorder: "no",
                                            scrolling: "no",
                                            src: "about:blank",
                                            mozallowfullscreen: "mozallowfullscreen",
                                            webkitallowfullscreen: "webkitallowfullscreen",
                                            allowfullscreen: "allowfullscreen",
                                            style: {
                                                width: this.size[0] + "px",
                                                height: this.size[1] + "px",
                                                overflow: "hidden"
                                            }
                                        });
                                    t && t.parentNode ? (t.parentNode.replaceChild(a, t), e()) : (document.body.appendChild(a), e(), document.body.removeChild(a))
                                }
                            }
                        },
                            {
                                "./createElement": 7,
                                "./extend": 9,
                                "./parseDOMByClassNames": 11,
                                "./player.css": 12,
                                "./player.html": 13
                            }],
                        3: [function (e, t) {
                            function n(e) {
                                e.strokeStyle = "black",
                                    e.lineWidth = 3,
                                    e.font = 'bold 20px "PingHei","Lucida Grande", "Lucida Sans Unicode", "STHeiti", "Helvetica","Arial","Verdana","sans-serif"'
                            }

                            var i = (e("./createElement"), .1),
                                o = 25,
                                r = 4e3,
                                a = document.createElement("canvas").getContext("2d");
                            n(a);
                            var s = window.requestAnimationFrame || window.mozRequestAnimationFrame || window.webkitRequestAnimationFrame || window.msRequestAnimationFrame || window.oRequestAnimationFrame ||
                                function (e) {
                                    setTimeout(e, 1e3 / 60)
                                };
                            t.exports = {
                                init: function () {
                                    this.video.addEventListener("play", this.reStartComment.bind(this)),
                                        this.video.addEventListener("pause", this.pauseComment.bind(this)),
                                        this.lastCommnetUpdateTime = 0,
                                        this.lastCommnetIndex = 0,
                                        this.commentLoopPreQueue = [],
                                        this.commentLoopQueue = [],
                                        this.commentButtonPreQueue = [],
                                        this.commentButtonQueue = [],
                                        this.commentTopPreQueue = [],
                                        this.commentTopQueue = [],
                                        this.drawQueue = [],
                                        this.preRenders = [],
                                        this.preRenderMap = {},
                                        this.enableComment = void 0 === this.comments ? !1 : !0,
                                        this.prevDrawCanvas = document.createElement("canvas"),
                                        this.canvas = this.DOMs.comments.getContext("2d"),
                                    this.comments && this.DOMs.player.classList.add("has-comments"),
                                        this.DOMs["comments-btn"].classList.add("enable"),
                                        this.DOMs.comments.display = this.enableComment ? "block" : "none";
                                    var e = 0,
                                        t = function () {
                                            (e = ~e) && this.onCommentTimeUpdate(),
                                                s(t)
                                        }.bind(this);
                                    t()
                                },
                                needDrawText: function (e, t, n) {
                                    this.drawQueue.push([e, t, n])
                                },
                                drawText: function () {
                                    var e = this.prevDrawCanvas,
                                        t = this.prevDrawCanvas.getContext("2d");
                                    e.width = this.canvasWidth,
                                        e.height = this.canvasHeight,
                                        t.clearRect(0, 0, this.canvasWidth, this.canvasHeight);
                                    var i = [];
                                    this.preRenders.forEach(function (e, t) {
                                        e.used = !1,
                                        void 0 === e.cid && i.push(t)
                                    });
                                    for (var r; r = this.drawQueue.shift();)!
                                        function (e, r) {
                                            var a, s = e[0].text + e[0].color,
                                                l = r.preRenderMap[s];
                                            if (void 0 === l) {
                                                var l = i.shift();
                                                void 0 === l ? (a = document.createElement("canvas"), l = r.preRenders.push(a) - 1) : a = r.preRenders[l];
                                                var c = a.width = e[0].width,
                                                    d = a.height = o + 10,
                                                    u = a.getContext("2d");
                                                u.clearRect(0, 0, c, d),
                                                    n(u),
                                                    u.fillStyle = e[0].color,
                                                    u.strokeText(e[0].text, 0, o),
                                                    u.fillText(e[0].text, 0, o),
                                                    a.cid = s,
                                                    r.preRenderMap[s] = l
                                            } else a = r.preRenders[l];
                                            a.used = !0,
                                                t.drawImage(a, e[1], e[2])
                                        }(r, this);
                                    this.preRenders.forEach(function (e) {
                                        e.used === !1 && (delete this.preRenderMap[e.cid], e.cid = void 0)
                                    }.bind(this)),
                                        this.canvas.clearRect(0, 0, this.canvasWidth, this.canvasHeight),
                                        this.canvas.drawImage(e, 0, 0)
                                },
                                createComment: function (e, t) {
                                    if (void 0 === e) return !1;
                                    var n = a.measureText(e.text);
                                    return {
                                        startTime: t,
                                        text: e.text,
                                        color: e.color,
                                        width: n.width + 20
                                    }
                                },
                                commentTop: function (e, t, n) {
                                    this.commentTopQueue.forEach(function (t, i) {
                                        void 0 != t && (n > t.startTime + r ? this.commentTopQueue[i] = void 0 : this.needDrawText(t, (e - t.width) / 2, o * i))
                                    }.bind(this));
                                    for (var i; i = this.commentTopPreQueue.shift();) i = this.createComment(i, n),
                                        this.commentTopQueue.forEach(function (t, n) {
                                            i && void 0 === t && (t = this.commentTopQueue[n] = i, this.needDrawText(t, (e - i.width) / 2, o * n), i = void 0)
                                        }.bind(this)),
                                    i && (this.commentTopQueue.push(i), this.needDrawText(i, (e - i.width) / 2, o * this.commentTopQueue.length - 1))
                                },
                                commentBottom: function (e, t, n) {
                                    t -= 10,
                                        this.commentButtonQueue.forEach(function (i, a) {
                                            void 0 != i && (n > i.startTime + r ? this.commentButtonQueue[a] = void 0 : this.needDrawText(i, (e - i.width) / 2, t - o * (a + 1)))
                                        }.bind(this));
                                    for (var i; i = this.commentButtonPreQueue.shift();) i = this.createComment(i, n),
                                        this.commentButtonQueue.forEach(function (n, r) {
                                            i && void 0 === n && (n = this.commentButtonQueue[r] = i, this.needDrawText(n, (e - i.width) / 2, t - o * (r + 1)), i = void 0)
                                        }.bind(this)),
                                    i && (this.commentButtonQueue.push(i), this.needDrawText(i, (e - i.width) / 2, t - o * this.commentButtonQueue.length))
                                },
                                commentLoop: function (e, t, n) {
                                    for (var r = t / o | 0, a = -1; ++a < r;) {
                                        var s = this.commentLoopQueue[a];
                                        if (void 0 === s && (s = this.commentLoopQueue[a] = []), this.commentLoopPreQueue.length > 0) {
                                            var l = 0 === s.length ? void 0 : s[s.length - 1];
                                            if (void 0 === l || (n - l.startTime) * i > l.width) {
                                                var c = this.createComment(this.commentLoopPreQueue.shift(), n);
                                                c && s.push(c)
                                            }
                                        }
                                        this.commentLoopQueue[a] = s.filter(function (t) {
                                            var r = (n - t.startTime) * i;
                                            return 0 > r || r > t.width + e ? !1 : (this.needDrawText(t, e - r, o * a), !0)
                                        }.bind(this))
                                    }
                                    for (var d = this.commentLoopQueue.length - r; d-- > 0;) this.commentLoopQueue.pop()
                                },
                                pauseComment: function () {
                                    this.pauseCommentAt = Date.now()
                                },
                                reStartComment: function () {
                                    if (this.pauseCommentAt) {
                                        var e = Date.now() - this.pauseCommentAt;
                                        this.commentLoopQueue.forEach(function (t) {
                                            t.forEach(function (t) {
                                                t && (t.startTime += e)
                                            })
                                        }),
                                            this.commentButtonQueue.forEach(function (t) {
                                                t && (t.startTime += e)
                                            }),
                                            this.commentTopQueue.forEach(function (t) {
                                                t && (t.startTime += e)
                                            })
                                    }
                                    this.pauseCommentAt = void 0
                                },
                                drawComment: function () {
                                    if (!this.pauseCommentAt) {
                                        var e = Date.now(),
                                            t = this.DOMs["video-frame"].offsetWidth,
                                            n = this.DOMs["video-frame"].offsetHeight;
                                        t != this.canvasWidth && (this.DOMs.comments.width = t, this.canvasWidth = t),
                                        n != this.canvasHeight && (this.DOMs.comments.height = n, this.canvasHeight = n);
                                        var i = this.video.offsetWidth,
                                            o = this.video.offsetHeight;
                                        this.commentLoop(i, o, e),
                                            this.commentTop(i, o, e),
                                            this.commentBottom(i, o, e),
                                            this.drawText()
                                    }
                                },
                                onCommentTimeUpdate: function () {
                                    if (this.enableComment !== !1) {
                                        var e = this.video.currentTime;
                                        if (Math.abs(e - this.lastCommnetUpdateTime) <= 1 && e > this.lastCommnetUpdateTime) {
                                            var t = 0;
                                            for (this.lastCommnetIndex && this.comments[this.lastCommnetIndex].time <= this.lastCommnetUpdateTime && (t = this.lastCommnetIndex); ++t < this.comments.length;) if (!(this.comments[t].time <= this.lastCommnetUpdateTime)) {
                                                if (this.comments[t].time > e) break;
                                                switch (this.comments[t].pos) {
                                                    case "bottom":
                                                        this.commentButtonPreQueue.push(this.comments[t]);
                                                        break;
                                                    case "top":
                                                        this.commentTopPreQueue.push(this.comments[t]);
                                                        break;
                                                    default:
                                                        this.commentLoopPreQueue.push(this.comments[t])
                                                }
                                                this.lastCommnetIndex = t
                                            }
                                        }
                                        try {
                                            this.drawComment()
                                        } catch (n) {
                                        }
                                        this.lastCommnetUpdateTime = e
                                    }
                                }
                            }
                        },
                            {
                                "./createElement": 7
                            }],
                        4: [function (e, t) {
                            function n(e) {
                                return Array.prototype.slice.call(e)
                            }

                            function i(e, t, n, i) {
                                function o(t) {
                                    var n = (t.clientX - e.parentNode.getBoundingClientRect().left) / e.parentNode.offsetWidth;
                                    return Math.min(Math.max(n, 0), 1)
                                }

                                function r(t) {
                                    1 == t.which && (l = !0, e.draging = !0, a(t))
                                }

                                function a(e) {
                                    if (1 == e.which && l === !0) {
                                        var t = o(e);
                                        n(t)
                                    }
                                }

                                function s(t) {
                                    if (1 == t.which && l === !0) {
                                        var r = o(t);
                                        n(r),
                                            i(r),
                                            l = !1,
                                            delete e.draging
                                    }
                                }

                                var l = !1;
                                n = n ||
                                    function () {
                                    },
                                    i = i ||
                                        function () {
                                        },
                                    e.parentNode.addEventListener("mousedown", r),
                                    t.addEventListener("mousemove", a),
                                    t.addEventListener("mouseup", s)
                            }

                            var o = (e("./createElement"), e("./delegateClickByClassName")),
                                r = e("./timeFormat");
                            t.exports = {
                                init: function () {
                                    var e = this.iframe.contentDocument,
                                        t = o(e);
                                    t.on("play", this.onPlayClick, this),
                                        t.on("video-frame", this.onVideoClick, this),
                                        t.on("source", this.onSourceClick, this),
                                        t.on("allscreen", this.onAllScreenClick, this),
                                        t.on("fullscreen", this.onfullScreenClick, this),
                                        t.on("normalscreen", this.onNormalScreenClick, this),
                                        t.on("comments-btn", this.oncommentsBtnClick, this),
                                        t.on("airplay", this.onAirplayBtnClick, this),
                                        e.documentElement.addEventListener("keydown", this.onKeyDown.bind(this), !1),
                                        this.DOMs.player.addEventListener("mousemove", this.onMouseActive.bind(this)),
                                        i(this.DOMs.progress_anchor, e, this.onProgressAnchorWillSet.bind(this), this.onProgressAnchorSet.bind(this)),
                                        i(this.DOMs.volume_anchor, e, this.onVolumeAnchorWillSet.bind(this))
                                },
                                onKeyDown: function (e) {
                                    switch (e.preventDefault(), e.keyCode) {
                                        case 32:
                                            this.onPlayClick();
                                            break;
                                        case 39:
                                            this.video.currentTime = Math.min(this.video.duration, this.video.currentTime + 10);
                                            break;
                                        case 37:
                                            this.video.currentTime = Math.max(0, this.video.currentTime - 10);
                                            break;
                                        case 38:
                                            this.video.volume = Math.min(1, this.video.volume + .1),
                                                this.DOMs.volume_anchor.style.width = 100 * this.video.volume + "%";
                                            break;
                                        case 40:
                                            this.video.volume = Math.max(0, this.video.volume - .1),
                                                this.DOMs.volume_anchor.style.width = 100 * this.video.volume + "%";
                                            break;
                                        case 65:
                                            this.DOMs.player.classList.contains("allscreen") ? this.onNormalScreenClick() : this.onAllScreenClick();
                                            break;
                                        case 70:
                                            this.DOMs.player.classList.contains("fullscreen") || this.onfullScreenClick()
                                    }
                                },
                                onVideoClick: function () {
                                    void 0 == this.videoClickDblTimer ? this.videoClickDblTimer = setTimeout(function () {
                                            this.videoClickDblTimer = void 0,
                                                this.onPlayClick()
                                        }.bind(this), 300) : (clearTimeout(this.videoClickDblTimer), this.videoClickDblTimer = void 0, document.fullscreenElement || document.mozFullScreenElement || document.webkitFullscreenElement ? this.onNormalScreenClick() : this.onfullScreenClick())
                                },
                                onMouseActive: function () {
                                    this.DOMs.player.classList.add("active"),
                                        clearTimeout(this.MouseActiveTimer),
                                        this.MouseActiveTimer = setTimeout(function () {
                                            this.DOMs.player.classList.remove("active")
                                        }.bind(this), 1e3)
                                },
                                onPlayClick: function () {
                                    this.DOMs.play.classList.contains("paused") ? (this.video.play(), this.DOMs.play.classList.remove("paused")) : (this.video.pause(), this.DOMs.play.classList.add("paused"))
                                },
                                onSourceClick: function (e) {
                                    e.classList.contains("curr") || (this.video.preloadStartTime = this.video.currentTime, this.video.src = this.sourceList[0 | e.getAttribute("sourceIndex")][1], n(e.parentNode.childNodes).forEach(function (t) {
                                        e === t ? t.classList.add("curr") : t.classList.remove("curr")
                                    }.bind(this)))
                                },
                                onProgressAnchorWillSet: function (e) {
                                    var t = this.video.duration,
                                        n = t * e;
                                    this.DOMs.current.innerHTML = r(n),
                                        this.DOMs.duration.innerHTML = r(t),
                                        this.DOMs.progress_anchor.style.width = 100 * e + "%"
                                },
                                onProgressAnchorSet: function (e) {
                                    this.video.currentTime = this.video.duration * e
                                },
                                onVolumeAnchorWillSet: function (e) {
                                    this.video.volume = e,
                                        this.DOMs.volume_anchor.style.width = 100 * e + "%"
                                },
                                onAllScreenClick: function () {
                                    var e = document.documentElement.clientWidth,
                                        t = document.documentElement.clientHeight;
                                    this.iframe.style.cssText = ";position:fixed;top:0;left:0;width:" + e + "px;height:" + t + "px;z-index:999999;",
                                        this.allScreenWinResizeFunction = this.allScreenWinResizeFunction ||
                                            function () {
                                                this.iframe.style.width = document.documentElement.clientWidth + "px",
                                                    this.iframe.style.height = document.documentElement.clientHeight + "px"
                                            }.bind(this),
                                        window.removeEventListener("resize", this.allScreenWinResizeFunction),
                                        window.addEventListener("resize", this.allScreenWinResizeFunction),
                                        this.DOMs.player.classList.add("allscreen")
                                },
                                onfullScreenClick: function () {
                                    ["webkitRequestFullScreen", "mozRequestFullScreen", "requestFullScreen"].forEach(function (e) {
                                        this.DOMs.player[e] && this.DOMs.player[e]()
                                    }.bind(this)),
                                        this.onMouseActive()
                                },
                                onNormalScreenClick: function () {
                                    window.removeEventListener("resize", this.allScreenWinResizeFunction),
                                        this.iframe.style.cssText = ";width:" + this.size[0] + "px;height:" + this.size[1] + "px;",
                                        ["webkitCancelFullScreen", "mozCancelFullScreen", "cancelFullScreen"].forEach(function (e) {
                                            document[e] && document[e]()
                                        }),
                                        this.DOMs.player.classList.remove("allscreen")
                                },
                                oncommentsBtnClick: function () {
                                    this.enableComment = !this.DOMs["comments-btn"].classList.contains("enable"),
                                        this.enableComment ? (setTimeout(function () {
                                                this.DOMs.comments.style.display = "block"
                                            }.bind(this), 80), this.DOMs["comments-btn"].classList.add("enable")) : (this.DOMs.comments.style.display = "none", this.DOMs["comments-btn"].classList.remove("enable"))
                                },
                                onAirplayBtnClick: function () {
                                    this.video.webkitShowPlaybackTargetPicker()
                                }
                            }
                        },
                            {
                                "./createElement": 7,
                                "./delegateClickByClassName": 8,
                                "./timeFormat": 14
                            }],
                        5: [function (e, t) {
                            var n = (e("./extend"), e("./createElement"));
                            e("./parseDOMByClassNames"),
                                t.exports = {
                                    init: function () {
                                        var e = 0;
                                        this.sourceList.forEach(function (t, i) {
                                            n("li", {
                                                appendTo: this.DOMs.hd,
                                                sourceIndex: i,
                                                className: "source " + (i === e ? "curr" : ""),
                                                innerHTML: t[0]
                                            })
                                        }.bind(this)),
                                            this.DOMs.video.src = this.sourceList[e][1]
                                    }
                                }
                        },
                            {
                                "./createElement": 7,
                                "./extend": 9,
                                "./parseDOMByClassNames": 11
                            }],
                        6: [function (e, t) {
                            var n = e("./timeFormat");
                            t.exports = {
                                init: function () {
                                    this.video.addEventListener("timeupdate", this.onVideoTimeUpdate.bind(this)),
                                        this.video.addEventListener("play", this.onVideoPlay.bind(this)),
                                        this.video.addEventListener("pause", this.onVideoTimePause.bind(this)),
                                        this.video.addEventListener("loadedmetadata", this.onVideoLoadedMetaData.bind(this)),
                                        this.video.addEventListener("webkitplaybacktargetavailabilitychanged", this.onPlaybackTargetAvailabilityChanged.bind(this)),
                                        setInterval(this.videoBuffered.bind(this), 1e3),
                                        this.DOMs.volume_anchor.style.width = 100 * this.video.volume + "%"
                                },
                                onVideoTimeUpdate: function () {
                                    var e = this.video.currentTime,
                                        t = this.video.duration;
                                    this.DOMs.current.innerHTML = n(e),
                                        this.DOMs.duration.innerHTML = n(t),
                                    this.DOMs.progress_anchor.draging || (this.DOMs.progress_anchor.style.width = 100 * Math.min(Math.max(e / t, 0), 1) + "%")
                                },
                                videoBuffered: function () {
                                    var e = this.video.buffered,
                                        t = this.video.currentTime,
                                        n = 0 == e.length ? 0 : e.end(e.length - 1);
                                    this.DOMs.buffered_anchor.style.width = 100 * Math.min(Math.max(n / this.video.duration, 0), 1) + "%",
                                        0 == n || t >= n ? this.DOMs.player.classList.add("loading") : this.DOMs.player.classList.remove("loading")
                                },
                                onVideoPlay: function () {
                                    this.DOMs.play.classList.remove("paused")
                                },
                                onVideoTimePause: function () {
                                    this.DOMs.play.classList.add("paused")
                                },
                                onVideoLoadedMetaData: function () {
                                    this.video.preloadStartTime && (this.video.currentTime = this.video.preloadStartTime, delete this.video.preloadStartTime)
                                },
                                onPlaybackTargetAvailabilityChanged: function (e) {
                                    var t = "support-airplay";
                                    "available" === e.availability ? this.DOMs.player.classList.add(t) : this.DOMs.player.classList.remove(t)
                                }
                            }
                        },
                            {
                                "./timeFormat": 14
                            }],
                        7: [function (e, t) {
                            function n(e, t) {
                                var n = document.createElement(e);
                                if ("function" == typeof t) t.call(n);
                                else for (var i in t) if (t.hasOwnProperty(i)) switch (i) {
                                    case "appendTo":
                                        t[i].appendChild(n);
                                        break;
                                    case "text":
                                        var o = document.createTextNode(t[i]);
                                        n.innerHTML = "",
                                            n.appendChild(o);
                                        break;
                                    case "innerHTML":
                                    case "className":
                                    case "id":
                                        n[i] = t[i];
                                        break;
                                    case "style":
                                        var r = t[i];
                                        for (var a in r) r.hasOwnProperty(a) && (n.style[a] = r[a]);
                                        break;
                                    default:
                                        n.setAttribute(i, t[i] + "")
                                }
                                return n
                            }

                            t.exports = n
                        },
                            {}],
                        8: [function (e, t) {
                            function n(e) {
                                return Array.prototype.slice.call(e)
                            }

                            function i(e) {
                                this._eventMap = {},
                                    this._rootElement = e,
                                    this._isRootElementBindedClick = !1,
                                    this._bindClickFunction = function (e) {
                                        !
                                            function t(e, i) {
                                                i && i.nodeName && (i.classList && n(i.classList).forEach(function (t) {
                                                    e.trigger(t, i)
                                                }), t(e, i.parentNode))
                                            }(this, e.target)
                                    }.bind(this)
                            }

                            var o = e("./extend");
                            o(i.prototype, {
                                on: function (e, t, n) {
                                    void 0 === this._eventMap[e] && (this._eventMap[e] = []),
                                        this._eventMap[e].push([t, n]),
                                    this._isRootElementBindedClick || (_isRootElementBindedClick = !0, this._rootElement.addEventListener("click", this._bindClickFunction, !1))
                                },
                                off: function (e, t) {
                                    if (void 0 != this._eventMap[e]) for (var n = this._eventMap[e].length; n--;) if (this._eventMap[e][n][0] === t) {
                                        this._eventMap[e].splice(n, 1);
                                        break
                                    }
                                    for (var i in this._eventMap) break;
                                    void 0 === i && this._isRootElementBindedClick && (_isRootElementBindedClick = !1, this._rootElement.removeEventListener("click", this._bindClickFunction, !1))
                                },
                                trigger: function (e, t) {
                                    t = void 0 === t ? this._rootElement.getElementsByTagNames(e) : [t],
                                        t.forEach(function (t) {
                                            (this._eventMap[e] || []).forEach(function (e) {
                                                e[0].call(e[1], t)
                                            })
                                        }.bind(this))
                                }
                            }),
                                t.exports = function (e) {
                                    return new i(e)
                                }
                        },
                            {
                                "./extend": 9
                            }],
                        9: [function (e, t) {
                            function n(e) {
                                for (var t, n = arguments.length, i = 1; n > i;) {
                                    t = arguments[i++];
                                    for (var o in t) t.hasOwnProperty(o) && (e[o] = t[o])
                                }
                                return e
                            }

                            t.exports = n
                        },
                            {}],
                        10: [function (e) {
                            function t(e, t, n, i) {
                                this.id = e,
                                    this.size = t.split("x"),
                                    this.sourceList = n || [],
                                    this.comments = i,
                                    this.init()
                            }

                            e("./component")(t, e("./component_build"), e("./component_event"), e("./component_video"), e("./component_source"), e("./component_comments")),
                                n = t
                        },
                            {
                                "./component": 1,
                                "./component_build": 2,
                                "./component_comments": 3,
                                "./component_event": 4,
                                "./component_source": 5,
                                "./component_video": 6
                            }],
                        11: [function (e, t) {
                            function n(e, t) {
                                var n = {};
                                return t.forEach(function (t) {
                                    n[t] = e.getElementsByClassName(t)[0]
                                }),
                                    n
                            }

                            t.exports = n
                        },
                            {}],
                        12: [function (e, t) {
                            t.exports = '* { margin:0; padding:0; }body { font-family: "PingHei","Lucida Grande", "Lucida Sans Unicode", "STHeiti", "Helvetica","Arial","Verdana","sans-serif"; font-size:16px;}html, body, .player { height: 100%; }.player:-webkit-full-screen { width: 100%; cursor:url(data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==); }.player:-moz-full-screen { width: 100%; cursor:url(data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==); }.player:full-screen { width: 100%; cursor:url(data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==); }.player { border-radius: 3px; overflow: hidden; position: relative; cursor: default;  -webkit-user-select: none;  -moz-user-select: none; user-select: none;}.video-frame { box-sizing: border-box; padding-bottom: 50px; height: 100%; overflow: hidden; position: relative;}.video-frame .comments{ position: absolute; top:0;left:0; width:100%; height:100%;  -webkit-transform:translateZ(0);  -moz-transform:translateZ(0); transform:translateZ(0);  pointer-events: none;}.player:-webkit-full-screen .video-frame { padding-bottom: 0px; }.player:-moz-full-screen .video-frame { padding-bottom: 0px; }.player:full-screen .video-frame{ padding-bottom: 0px; }.video { width: 100%;  height: 100%; background: #000000;}.controller {  position: absolute; bottom: 0px;  left:0; right:0;  background: #24272A;  height: 50px;}.controller .loading-icon { display: none;  position: absolute; width: 20px;  height: 20px; line-height: 20px;  text-align: center; font-size: 20px;  color: #ffffff; top: -30px; right: 10px;}.player.loading .controller .loading-icon {  display: block;}.player:-webkit-full-screen .controller { -webkit-transform:translateY(50px); -webkit-transition: -webkit-transform 0.3s ease;}.player:-moz-full-screen .controller { -moz-transform:translateY(50px);  -moz-transition: -moz-transform 0.3s ease;}.player:full-screen .controller {  transform:translateY(50px); transition: transform 0.3s ease;}.player.active:-webkit-full-screen { cursor: default;}.player.active:-moz-full-screen {  cursor: default;}.player.active:full-screen { cursor: default;}.player.active:-webkit-full-screen .controller,.player:-webkit-full-screen .controller:hover { -webkit-transform:translateY(0);  cursor: default;}.player.active:-moz-full-screen .controller,.player:-moz-full-screen .controller:hover { -moz-transform:translateY(0); cursor: default;}.player.active:full-screen .controller.player:full-screen .controller:hover {  transform:translateY(0);  cursor: default;}.player.active:-webkit-full-screen .controller .progress .progress_anchor:after,.player:-webkit-full-screen .controller:hover .progress .progress_anchor:after { height:12px;}.player.active:-moz-full-screen .controller .progress .progress_anchor:after,.player:-moz-full-screen .controller:hover .progress .progress_anchor:after { height:12px;}.player.active:full-screen .controller .progress .progress_anchor:after,.player:full-screen .controller:hover .progress .progress_anchor:after { height:12px;}.player:-webkit-full-screen .controller .progress .progress_anchor:after { height:4px;}.player:-moz-full-screen .controller .progress .progress_anchor:after { height:4px;}.player:full-screen .controller .progress .progress_anchor:after {  height:4px;}.controller .progress { position: absolute; top:0px;  left:0; right:0;  border-right: 4px solid #181A1D;  border-left: 8px solid #B3ABAB; height: 4px;  background: #181A1D;  z-index:1;  -webkit-transform: translateZ(0); -moz-transform: translateZ(0);  transform: translateZ(0);}.controller .progress:after { content:""; display: block; position: absolute; top:0px;  left:0; right:0;  bottom:-10px; height: 10px;}.controller .progress .anchor { height: 4px;  background: #B3ABAB;  position: absolute; top:0;left:0;}.controller .progress .anchor:after { content:""; display: block; width: 12px;  background: #f5f5f5;  position: absolute; right:-4px; top: 50%; height: 12px; box-shadow: 0 0 2px rgba(0,0,0, 0.4); border-radius: 12px;  -webkit-transform: translateY(-50%);  -moz-transform: translateY(-50%); transform: translateY(-50%);}.controller .progress .anchor.buffered_anchor {  position: relative; background: rgba(255,255,255,0.1);}.controller .progress .anchor.buffered_anchor:after {  box-shadow: none; height: 4px;  width: 4px; border-radius: 0; background: rgba(255,255,255,0.1);}.controller .right { height: 50px; position: absolute; top:0;  left:10px;  right:10px; pointer-events: none;}.controller .play,.controller .volume,.controller .time,.controller .hd,.controller .airplay,.controller .allscreen,.controller .normalscreen,.controller .comments-btn,.controller .fullscreen { padding-top:4px;  height: 46px; line-height: 50px;  text-align: center; color: #eeeeee; float:left; text-shadow:0 0 2px rgba(0,0,0,0.5);  pointer-events: auto;}.controller .hd,.controller .airplay,.controller .allscreen,.controller .normalscreen,.controller .comments-btn,.controller .fullscreen { float:right;}.controller .play {  width: 36px;  padding-left: 10px; cursor: pointer;}.controller .play:after {  font-family: "FontAwesome"; content: "\\f04c";}.controller .play.paused:after { content: "\\f04b";}.controller .volume {  min-width: 30px;  position: relative; overflow: hidden; -webkit-transition: min-width 0.3s ease 0.5s; -moz-transition: min-width 0.3s ease 0.5s;  transition: min-width 0.3s ease 0.5s;}.controller .volume:hover { min-width: 128px;}.controller .volume:before {  font-family: "FontAwesome"; content: "\\f028";  width: 36px;  display: block;}.controller .volume .progress { width: 70px;  top: 27px;  left: 40px;}.controller .time { font-size: 12px;  font-weight: bold;  padding-left: 10px;}.controller .time .current {  color: #EEEEEE;}.controller .fullscreen,.controller .airplay,.controller .allscreen,.controller .comments-btn,.controller .normalscreen { width: 36px;  cursor: pointer;}.controller .comments-btn {  margin-right: -15px;  display: none;}.player.has-comments .controller .comments-btn { display: block;}.controller .comments-btn:before {  font-family: "FontAwesome"; content: "\\f075";}.controller .comments-btn.enable:before {  color: #DF6558;}.controller .airplay,.controller .normalscreen {  display: none;}.player:-webkit-full-screen .controller .fullscreen,.player:-webkit-full-screen .controller .allscreen { display: none;}.player:-webkit-full-screen .controller .normalscreen,.player.allscreen .controller .normalscreen,.player.support-airplay .controller .airplay { display: block;}.player.allscreen .controller .allscreen {  display: none;}.controller .fullscreen:before { font-family: "FontAwesome"; content: "\\f0b2";}.controller .allscreen:before {  font-family: "FontAwesome"; content: "\\f065";}.controller .normalscreen:before { font-family: "FontAwesome"; content: "\\f066";}.controller .airplay { background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0ibWFtYS1haXJwbGF5LWljb24iIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IiB3aWR0aD0iMjJweCIgaGVpZ2h0PSIxNnB4IiB2aWV3Qm94PSIwIDAgMjIgMTYiIHhtbDpzcGFjZT0icHJlc2VydmUiPjxwb2x5bGluZSBwb2ludHM9IjUsMTIgMSwxMiAxLDEgMjEsMSAyMSwxMiAxNywxMiIgc3R5bGU9ImZpbGw6dHJhbnNwYXJlbnQ7c3Ryb2tlOndoaXRlO3N0cm9rZS13aWR0aDoxIi8+PHBvbHlsaW5lIHBvaW50cz0iNCwxNiAxMSwxMCAxOCwxNiIgc3R5bGU9ImZpbGw6d2hpdGU7c3Ryb2tlOnRyYW5zcGFyZW50O3N0cm9rZS13aWR0aDowIi8+PC9zdmc+DQo=) no-repeat center 20px;  background-size: 22px auto;}.controller .hd { white-space:nowrap; overflow: hidden; margin-right: 10px; text-align: right;}.controller .hd:hover li { max-width: 300px;}.controller .hd li {  display: inline-block;  max-width: 0px; -webkit-transition: max-width 0.8s ease 0.3s; -moz-transition: max-width 0.8s ease 0.3s;  transition: max-width 0.8s ease 0.3s; overflow: hidden; font-size: 14px;  font-weight: bold;  position: relative; cursor: pointer;}.controller .hd li:before {  content: "";  display: inline-block;  width:20px;}.controller .hd li:before { content: "";  display: inline-block;  width:20px;}.controller .hd li.curr { max-width: 300px; cursor: default;  color: #EEEEEE;}.controller .hd li.curr:after { content: "";  display: block; position: absolute; width:4px;  height:4px; border-radius: 50%; background: #ffffff;  left: 12px; top: 23px;  opacity: 0; -webkit-transition: opacity 0.5s ease 0.3s; -moz-transition: opacity 0.5s ease 0.3s;  transition: opacity 0.5s ease 0.3s;}'
                        },
                            {}],
                        13: [function (e, t) {
                            t.exports = '<div class="player">  <div class="video-frame"><video class="video" autoplay="autoplay"></video><canvas class="comments"></canvas></div>  <div class="controller">    <div class="loading-icon fa fa-spin fa-circle-o-notch"></div>   <div class="progress">      <div class="anchor buffered_anchor" style="width:0%"></div>     <div class="anchor progress_anchor" style="width:0%"></div>   </div>    <div class="right">     <div class="fullscreen"></div>      <div class="allscreen"></div>     <div class="normalscreen"></div>      <div class="airplay"></div>     <ul class="hd"></ul>      <div class="comments-btn"></div>     </div>    <div class="left">     <div class="play paused"></div>     <div class="volume">        <div class="progress">          <div class="anchor volume_anchor" style="width:0%"></div>       </div>      </div>      <div class="time">        <span class="current">00:00:00</span> / <span class="duration">00:00:00</span>      </div>     </div> </div></div>'
                        },
                            {}],
                        14: [function (e, t) {
                            function n(e, t) {
                                return (Array(t).join(0) + e).slice(-t)
                            }

                            function i(e) {
                                var t, i = [];
                                return [3600, 60, 1].forEach(function (o) {
                                    i.push(n(t = e / o | 0, 2)),
                                        e -= t * o
                                }),
                                    i.join(":")
                            }

                            t.exports = i
                        },
                            {}]
                    }, {}, [10]),
                    t.exports = n
            },
                {}],
            10: [function (e, t) {
                function n(e, t) {
                    for (var n = decodeURI(e), i = f[t ? "strict" : "loose"].exec(n), o = {
                        attr: {},
                        param: {},
                        seg: {}
                    }, r = 14; r--;) o.attr[p[r]] = i[r] || "";
                    return o.param.query = a(o.attr.query),
                        o.param.fragment = a(o.attr.fragment),
                        o.seg.path = o.attr.path.replace(/^\/+|\/+$/g, "").split("/"),
                        o.seg.fragment = o.attr.fragment.replace(/^\/+|\/+$/g, "").split("/"),
                        o.attr.base = o.attr.host ? (o.attr.protocol ? o.attr.protocol + "://" + o.attr.host : o.attr.host) + (o.attr.port ? ":" + o.attr.port : "") : "",
                        o
                }

                function i(e, t) {
                    if (0 === e[t].length) return e[t] = {};
                    var n = {};
                    for (var i in e[t]) n[i] = e[t][i];
                    return e[t] = n,
                        n
                }

                function o(e, t, n, r) {
                    var a = e.shift();
                    if (a) {
                        var s = t[n] = t[n] || [];
                        "]" == a ? d(s) ? "" !== r && s.push(r) : "object" == typeof s ? s[u(s).length] = r : s = t[n] = [t[n], r] : ~a.indexOf("]") ? (a = a.substr(0, a.length - 1), !v.test(a) && d(s) && (s = i(t, n)), o(e, s, a, r)) : (!v.test(a) && d(s) && (s = i(t, n)), o(e, s, a, r))
                    } else d(t[n]) ? t[n].push(r) : t[n] = "object" == typeof t[n] ? r : "undefined" == typeof t[n] ? r : [t[n], r]
                }

                function r(e, t, n) {
                    if (~t.indexOf("]")) {
                        var i = t.split("[");
                        o(i, e, "base", n)
                    } else {
                        if (!v.test(t) && d(e.base)) {
                            var r = {};
                            for (var a in e.base) r[a] = e.base[a];
                            e.base = r
                        }
                        "" !== t && s(e.base, t, n)
                    }
                    return e
                }

                function a(e) {
                    return c(String(e).split(/&|;/), function (e, t) {
                        try {
                            t = decodeURIComponent(t.replace(/\+/g, " "))
                        } catch (n) {
                        }
                        var i = t.indexOf("="),
                            o = l(t),
                            a = t.substr(0, o || i),
                            s = t.substr(o || i, t.length);
                        return s = s.substr(s.indexOf("=") + 1, s.length),
                        "" === a && (a = t, s = ""),
                            r(e, a, s)
                    }, {
                        base: {}
                    }).base
                }

                function s(e, t, n) {
                    var i = e[t];
                    "undefined" == typeof i ? e[t] = n : d(i) ? i.push(n) : e[t] = [i, n]
                }

                function l(e) {
                    for (var t, n, i = e.length, o = 0; i > o; ++o) if (n = e[o], "]" == n && (t = !1), "[" == n && (t = !0), "=" == n && !t) return o
                }

                function c(e, t) {
                    for (var n = 0, i = e.length >> 0, o = arguments[2]; i > n;) n in e && (o = t.call(void 0, o, e[n], n, e)),
                        ++n;
                    return o
                }

                function d(e) {
                    return "[object Array]" === Object.prototype.toString.call(e)
                }

                function u(e) {
                    var t = [];
                    for (var n in e) e.hasOwnProperty(n) && t.push(n);
                    return t
                }

                function h(e, t) {
                    return 1 === arguments.length && e === !0 && (t = !0, e = void 0),
                        t = t || !1,
                        e = e || window.location.toString(),
                        {
                            data: n(e, t),
                            attr: function (e) {
                                return e = m[e] || e,
                                    "undefined" != typeof e ? this.data.attr[e] : this.data.attr
                            },
                            param: function (e) {
                                return "undefined" != typeof e ? this.data.param.query[e] : this.data.param.query
                            },
                            fparam: function (e) {
                                return "undefined" != typeof e ? this.data.param.fragment[e] : this.data.param.fragment
                            },
                            segment: function (e) {
                                return "undefined" == typeof e ? this.data.seg.path : (e = 0 > e ? this.data.seg.path.length + e : e - 1, this.data.seg.path[e])
                            },
                            fsegment: function (e) {
                                return "undefined" == typeof e ? this.data.seg.fragment : (e = 0 > e ? this.data.seg.fragment.length + e : e - 1, this.data.seg.fragment[e])
                            }
                        }
                }

                var p = ["source", "protocol", "authority", "userInfo", "user", "password", "host", "port", "relative", "path", "directory", "file", "query", "fragment"],
                    m = {
                        anchor: "fragment"
                    },
                    f = {
                        strict: /^(?:([^:\/?#]+):)?(?:\/\/((?:(([^:@]*):?([^:@]*))?@)?([^:\/?#]*)(?::(\d*))?))?((((?:[^?#\/]*\/)*)([^?#]*))(?:\?([^#]*))?(?:#(.*))?)/,
                        loose: /^(?:(?![^:@]+:[^:@\/]*@)([^:\/?#.]+):)?(?:\/\/)?((?:(([^:@]*):?([^:@]*))?@)?([^:\/?#]*)(?::(\d*))?)(((\/(?:[^?#](?![^?#\/]*\.[^?#\/.]+(?:[?#]|$)))*\/?)?([^?#\/]*))(?:\?([^#]*))?(?:#(.*))?)/
                    },
                    v = /^[0-9]+$/;
                t.exports = h
            },
                {}],
            11: [function (e, t) {
                function n(e) {
                    var t = [];
                    for (var n in e) e.hasOwnProperty(n) && t.push([n, e[n]].join("="));
                    return t.join("&")
                }

                t.exports = n
            },
                {}],
            12: [function (e, t, n) {
                var i = e("./canPlayM3U8"),
                    o = e("./ajax");
                n.match = function (e) {
                    return /www\.hunantv\.com/.test(e.attr("host"))
                },
                    n.getVideos = function (e, t) {
                        if (i) {
                            var n = function (e) {
                                    var t = e.split("?")[1],
                                        n = new Array;
                                    n = t.split("&");
                                    var i = {};
                                    for (key in n) param = n[key],
                                        item = new Array,
                                        item = n[key].split("="),
                                    "" != item[0] && (i[item[0]] = item[1]);
                                    return i
                                },
                                r = "&fmt=6&pno=7&m3u8=1",
                                a = document.getElementsByName("FlashVars")[0].getAttribute("value"),
                                s = a.split("&file=")[1],
                                l = s.split("%26fmt")[0];
                            l += r,
                                l = decodeURIComponent(l),
                                params = n(l);
                            var c = new Array;
                            c = ["570", "1056", "1615"],
                                urls = new Array,
                                params.limitrate = c[0],
                                text = "\u6807\u6e05",
                                o({
                                    url: "http://pcvcr.cdn.imgo.tv/ncrs/vod.do",
                                    jsonp: !0,
                                    param: params,
                                    callback: function (e) {
                                        "ok" == e.status && urls.push([text, e.info]),
                                            params.limitrate = c[1],
                                            text = "\u9ad8\u6e05",
                                            o({
                                                url: "http://pcvcr.cdn.imgo.tv/ncrs/vod.do",
                                                jsonp: !0,
                                                param: params,
                                                callback: function (e) {
                                                    "ok" == e.status && urls.push([text, e.info]),
                                                        params.limitrate = c[2],
                                                        text = "\u8d85\u6e05",
                                                        o({
                                                            url: "http://pcvcr.cdn.imgo.tv/ncrs/vod.do",
                                                            jsonp: !0,
                                                            param: params,
                                                            callback: function (e) {
                                                                return "ok" == e.status && urls.push([text, e.info]),
                                                                    t(urls)
                                                            }
                                                        })
                                                }
                                            })
                                    }
                                })
                        } else console.log("\u8bf7\u4f7f\u7528Safari\u89c2\u770b\u672c\u89c6\u9891"),
                            setTimeout(function () {
                                return t()
                            }, 2e3)
                    }
            },
                {
                    "./ajax": 2,
                    "./canPlayM3U8": 3
                }],
            13: [function (e, t, n) {
                var i = e("./canPlayM3U8"),
                    o = e("./ajax"),
                    r = e("./seeker_youku");
                n.match = function (e) {
                    var t = window.iid || window.pageConfig && window.pageConfig.iid || window.itemData && window.itemData.iid,
                        n = window.itemData && window.itemData.vcode;
                    return /tudou\.com/.test(e.attr("host")) && (n || t)
                },
                    n.getVideos = function (e, t) {
                        var n = window.itemData && window.itemData.vcode;
                        if (n) return r.parseYoukuCode(n, t);
                        var a = window.iid || window.pageConfig && window.pageConfig.iid || window.itemData && window.itemData.iid,
                            s = function (e) {
                                var t, n = [
                                    ["\u539f\u753b", "http://vr.tudou.com/v2proxy/v2.m3u8?it=" + a + "&st=5"],
                                    ["\u8d85\u6e05", "http://vr.tudou.com/v2proxy/v2.m3u8?it=" + a + "&st=4"],
                                    ["\u9ad8\u6e05", "http://vr.tudou.com/v2proxy/v2.m3u8?it=" + a + "&st=3"],
                                    ["\u6807\u6e05", "http://vr.tudou.com/v2proxy/v2.m3u8?it=" + a + "&st=2"]
                                ];
                                window.itemData && window.itemData.segs && (n = [], t = JSON.parse(window.itemData.segs), t[5] && n.push(["\u539f\u753b", "http://vr.tudou.com/v2proxy/v2.m3u8?it=" + a + "&st=5"]), t[4] && n.push(["\u8d85\u6e05", "http://vr.tudou.com/v2proxy/v2.m3u8?it=" + a + "&st=4"]), t[3] && n.push(["\u9ad8\u6e05", "http://vr.tudou.com/v2proxy/v2.m3u8?it=" + a + "&st=3"]), t[2] && n.push(["\u6807\u6e05", "http://vr.tudou.com/v2proxy/v2.m3u8?it=" + a + "&st=2"])),
                                    console.log("\u89e3\u6790tudou\u89c6\u9891\u5730\u5740\u6210\u529f " + n.map(function (e) {
                                            return "<a href=" + e[1] + ">" + e[0] + "</a>"
                                        }).join(" ")),
                                    e(n)
                            },
                            l = function (e) {
                                o({
                                    url: "http://vr.tudou.com/v2proxy/v2.js",
                                    param: {
                                        it: a,
                                        st: "52%2C53%2C54"
                                    },
                                    jsonp: "jsonp",
                                    callback: function (t) {
                                        if (-1 === t || -1 == t.code) return console.log("\u89e3\u6790tudou\u89c6\u9891\u5730\u5740\u5931\u8d25");
                                        for (var n = [], i = 0, o = t.urls.length; o > i; i++) n.push([i, t.urls[i]]);
                                        return console.log("\u89e3\u6790tudou\u89c6\u9891\u5730\u5740\u6210\u529f " + n.map(function (e) {
                                                return "<a href=" + e[1] + ">" + e[0] + "</a>"
                                            }).join(" ")),
                                            e(n)
                                    }
                                })
                            };
                        i ? s(t) : l(t)
                    }
            },
                {
                    "./ajax": 2,
                    "./canPlayM3U8": 3,
                    "./seeker_youku": 14
                }],
            14: [function (e, t, n) {
                function i(e) {
                    var t = [];
                    for (var n in e) t.push(n + "=" + e[n]);
                    return t.join("&")
                }

                function o(e) {
                    if (!e) return "";
                    e = e.toString();
                    var t, n, i, o, r, a, s, l = new Array(-1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, 62, -1, -1, -1, 63, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, -1, -1, -1, -1, -1, -1, -1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, -1, -1, -1, -1, -1, -1, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, -1, -1, -1, -1, -1);
                    for (a = e.length, r = 0, s = ""; a > r;) {
                        do t = l[255 & e.charCodeAt(r++)];
                        while (a > r && -1 == t);
                        if (-1 == t) break;
                        do n = l[255 & e.charCodeAt(r++)];
                        while (a > r && -1 == n);
                        if (-1 == n) break;
                        s += String.fromCharCode(t << 2 | (48 & n) >> 4);
                        do {
                            if (i = 255 & e.charCodeAt(r++), 61 == i) return s;
                            i = l[i]
                        } while (a > r && -1 == i);
                        if (-1 == i) break;
                        s += String.fromCharCode((15 & n) << 4 | (60 & i) >> 2);
                        do {
                            if (o = 255 & e.charCodeAt(r++), 61 == o) return s;
                            o = l[o]
                        } while (a > r && -1 == o);
                        if (-1 == o) break;
                        s += String.fromCharCode((3 & i) << 6 | o)
                    }
                    return s
                }

                function r(e) {
                    if (!e) return "";
                    e = e.toString();
                    var t, n, i, o, r, a, s = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/";
                    for (i = e.length, n = 0, t = ""; i > n;) {
                        if (o = 255 & e.charCodeAt(n++), n == i) {
                            t += s.charAt(o >> 2),
                                t += s.charAt((3 & o) << 4),
                                t += "==";
                            break
                        }
                        if (r = e.charCodeAt(n++), n == i) {
                            t += s.charAt(o >> 2),
                                t += s.charAt((3 & o) << 4 | (240 & r) >> 4),
                                t += s.charAt((15 & r) << 2),
                                t += "=";
                            break
                        }
                        a = e.charCodeAt(n++),
                            t += s.charAt(o >> 2),
                            t += s.charAt((3 & o) << 4 | (240 & r) >> 4),
                            t += s.charAt((15 & r) << 2 | (192 & a) >> 6),
                            t += s.charAt(63 & a)
                    }
                    return t
                }

                function a(e, t) {
                    for (var n, i = [], o = 0, r = "", a = 0; 256 > a; a++) i[a] = a;
                    for (a = 0; 256 > a; a++) o = (o + i[a] + e.charCodeAt(a % e.length)) % 256,
                        n = i[a],
                        i[a] = i[o],
                        i[o] = n;
                    a = 0,
                        o = 0;
                    for (var s = 0; s < t.length; s++) a = (a + 1) % 256,
                        o = (o + i[a]) % 256,
                        n = i[a],
                        i[a] = i[o],
                        i[o] = n,
                        r += String.fromCharCode(t.charCodeAt(s) ^ i[(i[a] + i[o]) % 256]);
                    return r
                }

                function s(e, t) {
                    for (var n = [], i = 0; i < e.length; i++) {
                        var o = 0;
                        o = e[i] >= "a" && e[i] <= "z" ? e[i].charCodeAt(0) - "a".charCodeAt(0) : e[i] - "0" + 26;
                        for (var r = 0; 36 > r; r++) if (t[r] == o) {
                            o = r;
                            break
                        }
                        n[i] = o > 25 ? o - 26 : String.fromCharCode(o + 97)
                    }
                    return n.join("")
                }

                function l(e, t, n) {
                    var i = this;
                    new Date,
                        this._sid = m.sid,
                        this._fileType = n,
                        this._videoSegsDic = {},
                        this._ip = e.security.ip;
                    var o = (new c, []),
                        r = [];
                    r.streams = {},
                        r.logos = {},
                        r.typeArr = {},
                        r.totalTime = {};
                    for (var a = 0; a < t.length; a++) {
                        for (var s = t[a].audio_lang, l = !1, d = 0; d < o.length; d++) if (o[d] == s) {
                            l = !0;
                            break
                        }
                        l || o.push(s)
                    }
                    for (var a = 0; a < o.length; a++) {
                        for (var u = o[a], h = {}, p = {}, f = [], d = 0; d < t.length; d++) {
                            var v = t[d];
                            if (u == v.audio_lang) {
                                if (!i.isValidType(v.stream_type)) continue;
                                var g = i.convertType(v.stream_type),
                                    y = 0;
                                "none" != v.logo && (y = 1),
                                    p[g] = y;
                                var b = !1;
                                for (var w in f) g == f[w] && (b = !0);
                                b || f.push(g);
                                var x = v.segs;
                                if (null == x) continue;
                                var k = [];
                                b && (k = h[g]);
                                for (var A = 0; A < x.length; A++) {
                                    var C = x[A];
                                    if (null == C) break;
                                    var T = {};
                                    T.no = A,
                                        T.size = C.size,
                                        T.seconds = Number(C.total_milliseconds_video) / 1e3,
                                        T.milliseconds_video = Number(v.milliseconds_video) / 1e3,
                                        T.key = C.key,
                                        T.fileId = this.getFileId(v.stream_fileid, A),
                                        T.src = this.getVideoSrc(d, A, e, v.stream_type, T.fileId),
                                        T.type = g,
                                        k.push(T)
                                }
                                h[g] = k
                            }
                        }
                        var M = this.langCodeToCN(u).key;
                        r.logos[M] = p,
                            r.streams[M] = h,
                            r.typeArr[M] = f
                    }
                    this._videoSegsDic = r,
                        this._videoSegsDic.lang = this.langCodeToCN(o[0]).key
                }

                function c(e) {
                    this._randomSeed = e,
                        this.cg_hun()
                }

                var d = e("./canPlayM3U8"),
                    u = e("./ajax"),
                    h = [19, 1, 4, 7, 30, 14, 28, 8, 24, 17, 6, 35, 34, 16, 9, 10, 13, 22, 32, 29, 31, 21, 18, 3, 2, 23, 25, 27, 11, 20, 5, 15, 12, 0, 33, 26],
                    p = {
                        a3: "b4et",
                        a4: "boa4"
                    },
                    m = {
                        a1: "4",
                        a2: "1"
                    };
                n.match = function (e) {
                    return /v\.youku\.com/.test(e.attr("host")) && !!window.videoId
                },
                    n.parseYoukuCode = function (e, t) {
                        u({
                            url: "http://play.youku.com/play/get.json?vid=" + e + "&ct=12",
                            jsonp: !0,
                            callback: function (n) {
                                -1 == n && console.log("\u89e3\u6790youku\u89c6\u9891\u5730\u5740\u5931\u8d25", 2);
                                var c = n.data,
                                    u = a(s(p.a3 + "o0b" + m.a1, h).toString(), o(c.security.encrypt_string)).split("_");
                                if (m.sid = u[0], m.token = u[1], d) {
                                    var f = {
                                            vid: window.videoId,
                                            type: "[[type]]",
                                            ts: parseInt((new Date).getTime() / 1e3),
                                            keyframe: 0,
                                            ep: encodeURIComponent(r(a(s(p.a4 + "poz" + m.a2, h).toString(), m.sid + "_" + e + "_" + m.token))),
                                            sid: m.sid,
                                            token: m.token,
                                            ctype: 12,
                                            ev: 1,
                                            oip: c.security.ip,
                                            client_id: "youkumobileplaypage"
                                        },
                                        v = "http://pl.youku.com/playlist/m3u8?" + i(f);
                                    t([
                                        ["\u8d85\u6e05", v.replace("[[type]]", "hd2")],
                                        ["\u9ad8\u6e05", v.replace("[[type]]", "mp4")],
                                        ["\u6807\u6e05", v.replace("[[type]]", "flv")]
                                    ])
                                } else {
                                    var g = new l(c, c.stream, "mp4");
                                    console.log(g._videoSegsDic.streams),
                                        t([
                                            ["\u6807\u6e05", g._videoSegsDic.streams.guoyu["3gphd"][0].src]
                                        ])
                                }
                            }
                        })
                    },
                    n.getVideos = function (e, t) {
                        n.parseYoukuCode(window.videoId, t)
                    },
                    c.prototype = {
                        cg_hun: function () {
                            this._cgStr = "";
                            for (var e = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ/\\:._-1234567890", t = e.length, n = 0; t > n; n++) {
                                var i = parseInt(this.ran() * e.length);
                                this._cgStr += e.charAt(i),
                                    e = e.split(e.charAt(i)).join("")
                            }
                        },
                        cg_fun: function (e) {
                            for (var t = e.split("*"), n = "", i = 0; i < t.length - 1; i++) n += this._cgStr.charAt(t[i]);
                            return n
                        },
                        ran: function () {
                            return this._randomSeed = (211 * this._randomSeed + 30031) % 65536,
                            this._randomSeed / 65536
                        }
                    },
                    l.prototype = {
                        getFileId: function (e, t) {
                            if (null == e || "" == e) return "";
                            var n = "",
                                i = e.slice(0, 8),
                                o = t.toString(16);
                            1 == o.length && (o = "0" + o),
                                o = o.toUpperCase();
                            var r = e.slice(10, e.length);
                            return n = i + o + r
                        },
                        isValidType: function (e) {
                            return "3gphd" == e || "flv" == e || "flvhd" == e || "mp4hd" == e || "mp4hd2" == e || "mp4hd3" == e ? !0 : !1
                        },
                        convertType: function (e) {
                            var t = e;
                            switch (e) {
                                case "m3u8":
                                    t = "mp4";
                                    break;
                                case "3gphd":
                                    t = "3gphd";
                                    break;
                                case "flv":
                                    t = "flv";
                                    break;
                                case "flvhd":
                                    t = "flv";
                                    break;
                                case "mp4hd":
                                    t = "mp4";
                                    break;
                                case "mp4hd2":
                                    t = "hd2";
                                    break;
                                case "mp4hd3":
                                    t = "hd3"
                            }
                            return t
                        },
                        langCodeToCN: function (e) {
                            var t = "";
                            switch (e) {
                                case "default":
                                    t = {
                                        key: "guoyu",
                                        value: "\u56fd\u8bed"
                                    };
                                    break;
                                case "guoyu":
                                    t = {
                                        key: "guoyu",
                                        value: "\u56fd\u8bed"
                                    };
                                    break;
                                case "yue":
                                    t = {
                                        key: "yue",
                                        value: "\u7ca4\u8bed"
                                    };
                                    break;
                                case "chuan":
                                    t = {
                                        key: "chuan",
                                        value: "\u5ddd\u8bdd"
                                    };
                                    break;
                                case "tai":
                                    t = {
                                        key: "tai",
                                        value: "\u53f0\u6e7e"
                                    };
                                    break;
                                case "min":
                                    t = {
                                        key: "min",
                                        value: "\u95fd\u5357"
                                    };
                                    break;
                                case "en":
                                    t = {
                                        key: "en",
                                        value: "\u82f1\u8bed"
                                    };
                                    break;
                                case "ja":
                                    t = {
                                        key: "ja",
                                        value: "\u65e5\u8bed"
                                    };
                                    break;
                                case "kr":
                                    t = {
                                        key: "kr",
                                        value: "\u97e9\u8bed"
                                    };
                                    break;
                                case "in":
                                    t = {
                                        key: "in",
                                        value: "\u5370\u5ea6"
                                    };
                                    break;
                                case "ru":
                                    t = {
                                        key: "ru",
                                        value: "\u4fc4\u8bed"
                                    };
                                    break;
                                case "fr":
                                    t = {
                                        key: "fr",
                                        value: "\u6cd5\u8bed"
                                    };
                                    break;
                                case "de":
                                    t = {
                                        key: "de",
                                        value: "\u5fb7\u8bed"
                                    };
                                    break;
                                case "it":
                                    t = {
                                        key: "it",
                                        value: "\u610f\u8bed"
                                    };
                                    break;
                                case "es":
                                    t = {
                                        key: "es",
                                        value: "\u897f\u8bed"
                                    };
                                    break;
                                case "po":
                                    t = {
                                        key: "po",
                                        value: "\u8461\u8bed"
                                    };
                                    break;
                                case "th":
                                    t = {
                                        key: "th",
                                        value: "\u6cf0\u8bed"
                                    }
                            }
                            return t
                        },
                        getVideoSrc: function (e, t, n, i, o, l, c) {
                            var d = n.stream[e],
                                u = n.video.encodeid;
                            if (!u || !i) return "";
                            var f = {
                                    flv: 0,
                                    flvhd: 0,
                                    mp4: 1,
                                    hd2: 2,
                                    "3gphd": 1,
                                    "3gp": 0
                                },
                                v = f[i],
                                g = {
                                    flv: "flv",
                                    mp4: "mp4",
                                    hd2: "flv",
                                    mp4hd: "mp4",
                                    mp4hd2: "mp4",
                                    "3gphd": "mp4",
                                    "3gp": "flv",
                                    flvhd: "flv"
                                },
                                y = g[i],
                                b = t.toString(16);
                            1 == b.length && (b = "0" + b);
                            var w = d.segs[t].total_milliseconds_video / 1e3,
                                x = d.segs[t].key;
                            ("" == x || -1 == x) && (x = d.key2 + d.key1);
                            var k = "";
                            n.show && (k = n.show.pay ? "&ypremium=1" : "&ymovie=1");
                            var A = "/player/getFlvPath/sid/" + m.sid + "_" + b + "/st/" + y + "/fileid/" + o + "?K=" + x + "&hd=" + v + "&myp=0&ts=" + w + "&ypp=0" + k,
                                C = encodeURIComponent(r(a(s(p.a4 + "poz" + m.a2, h).toString(), m.sid + "_" + o + "_" + m.token)));
                            return A += "&ep=" + C,
                                A += "&ctype=12",
                                A += "&ev=1",
                                A += "&token=" + m.token,
                                A += "&oip=" + this._ip,
                                A += (l ? "/password/" + l : "") + (c ? c : ""),
                                A = "http://k.youku.com" + A
                        }
                    }
            },
                {
                    "./ajax": 2,
                    "./canPlayM3U8": 3
                }],
            15: [function (e, t) {
                t.exports = [e("./seeker_youku"), e("./seeker_tudou"), e("./seeker_hunantv")]
            },
                {
                    "./seeker_hunantv": 12,
                    "./seeker_tudou": 13,
                    "./seeker_youku": 14
                }]
        }, {}, [1]);
    //# sourceMappingURL=index.js.map
    </script>
    <script>doAdblock();
    function doAdblock() {
        (function () {
            function A() {
            }

            A.prototype = {
                rules: {
                    /*youku_loader: {
                     find: /^http:\/\/static\.youku\.com(\/v[\d\.]*)?\/v\/swf\/loaders?[^\.]*\.swf/,
                     replace: "http://2016.adtchrome.com/loader.swf"
                     },
                     youku_player: {
                     find: /^http:\/\/static\.youku\.com(\/v[\d\.]*)?\/v\/swf\/(q?player[^\.]*|\w{13})\.swf/,
                     replace: "http://2016.adtchrome.com/player.swf"
                     },*/
                    'pps_pps': {
                        'find': /^http:\/\/www\.iqiyi\.com\/player\/cupid\/common\/pps_flvplay_s\.swf/,
                        'replace': 'http://swf.adtchrome.com/pps_20140420.swf'
                    },
                    /*'iqiyi_1': {
                     'find': /^http:\/\/www\.iqiyi\.com\/player\/cupid\/common\/.+\.swf$/,
                     'replace': 'http://swf.adtchrome.com/iqiyi_20140624.swf'
                     },
                     'iqiyi_2': {
                     'find': /^http:\/\/www\.iqiyi\.com\/common\/flashplayer\/\d+\/.+\.swf$/,
                     'replace': 'http://swf.adtchrome.com/iqiyi_20140624.swf'
                     },*/
                    'ku6': {
                        'find': /^http:\/\/player\.ku6cdn\.com\/default\/.*\/\d+\/(v|player|loader)\.swf/,
                        'replace': 'http://swf.adtchrome.com/ku6_20140420.swf'
                    },
                    'ku6_topic': {
                        'find': /^http:\/\/player\.ku6\.com\/inside\/(.*)\/v\.swf/,
                        'replace': 'http://swf.adtchrome.com/ku6_20140420.swf?vid=$1'
                    },
                    /*'sohu': {
                     'find':/http:\/\/(tv\.sohu\.com\/upload\/swf\/(?!(ap|56)).*\d+|(\d+\.){3}\d+(:\d+)?\/(web|test)player)\/(Main|PlayerShell)[^\.]*\.swf/,
                     'replace': "http://adtchrome.b0.upaiyun.com/sohu_live.swf"
                     },
                     'letv': {
                     'find': /^http:\/\/player\.letvcdn\.com\/.*p\/.*\/newplayer\/LetvPlayer\.swf/,
                     'replace': 'http://swf.adtchrome.com/20150110_letv.swf'
                     },
                     'letv_topic': {
                     'find': /^http:\/\/player\.hz\.letv\.com\/hzplayer\.swf\/v_list=zhuanti/,
                     'replace': 'http://swf.adtchrome.com/20150110_letv.swf'
                     },
                     'letv_duowan': {
                     'find': /^http:\/\/assets\.dwstatic\.com\/video\/vpp\.swf/,
                     'replace': 'http://yuntv.letv.com/bcloud.swf'
                     },*/
                    '17173_in': {
                        'find': /http:\/\/f\.v\.17173cdn\.com\/(\d+\/)?flash\/PreloaderFile(Customer)?\.swf/,
                        'replace': "http://swf.adtchrome.com/17173_in_20150522.swf"
                    },
                    '17173_out': {
                        'find': /http:\/\/f\.v\.17173cdn\.com\/(\d+\/)?flash\/PreloaderFileFirstpage\.swf/,
                        'replace': "http://swf.adtchrome.com/17173_out_20150522.swf"
                    },
                    '17173_live': {
                        'find': /http:\/\/f\.v\.17173cdn\.com\/(\d+\/)?flash\/Player_stream(_firstpage)?\.swf/,
                        'replace': "http://swf.adtchrome.com/17173_stream_20150522.swf"
                    },
                    '17173_live_out': {
                        'find': /http:\/\/f\.v\.17173cdn\.com\/(\d+\/)?flash\/Player_stream_(custom)?Out\.swf/,
                        'replace': "http://swf.adtchrome.com/17173.out.Live.swf"
                    }
                },
                _done: null,
                get done() {
                    if (!this._done) {
                        this._done = new Array();
                    }
                    return this._done;
                },
                addAnimations: function () {
                    var style = document.createElement('style');
                    style.type = 'text/css';
                    style.innerHTML = 'object,embed{\
                -webkit-animation-duration:.001s;-webkit-animation-name:playerInserted;\
                -ms-animation-duration:.001s;-ms-animation-name:playerInserted;\
                -o-animation-duration:.001s;-o-animation-name:playerInserted;\
                animation-duration:.001s;animation-name:playerInserted;}\
                @-webkit-keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}\
                @-ms-keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}\
                @-o-keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}\
                @keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}';
                    document.getElementsByTagName('head')[0].appendChild(style);
                },
                animationsHandler: function (e) {
                    if (e.animationName === 'playerInserted') {
                        this.replace(e.target);
                    }
                },
                replace: function (elem) {
                    if (/http:\/\/v.youku.com\/v_show\/.*/.test(window.location.href)) {
                        var tag = document.getElementById("playerBox").getAttribute("player")
                        if (tag == "adt") {
                            console.log("adt adv")
                            return;
                        }
                    }
                    if (this.done.indexOf(elem) != -1) return;
                    this.done.push(elem);
                    var player = elem.data || elem.src;
                    if (!player) return;
                    var i, find, replace = false;
                    for (i in this.rules) {
                        find = this.rules[i]['find'];
                        if (find.test(player)) {
                            replace = this.rules[i]['replace'];
                            if ('function' === typeof this.rules[i]['preHandle']) {
                                this.rules[i]['preHandle'].bind(this, elem, find, replace, player)();
                            } else {
                                this.reallyReplace.bind(this, elem, find, replace)();
                            }
                            break;
                        }
                    }
                },
                reallyReplace: function (elem, find, replace) {
                    elem.data && (elem.data = elem.data.replace(find, replace)) || elem.src && ((elem.src = elem.src.replace(find, replace)) && (elem.style.display = 'block'));
                    var b = elem.querySelector("param[name='movie']");
                    this.reloadPlugin(elem);
                },
                reloadPlugin: function (elem) {
                    var nextSibling = elem.nextSibling;
                    var parentNode = elem.parentNode;
                    parentNode.removeChild(elem);
                    var newElem = elem.cloneNode(true);
                    this.done.push(newElem);
                    if (nextSibling) {
                        parentNode.insertBefore(newElem, nextSibling);
                    } else {
                        parentNode.appendChild(newElem);
                    }
                },
                init: function () {
                    var handler = this.animationsHandler.bind(this);
                    document.body.addEventListener('webkitAnimationStart', handler, false);
                    document.body.addEventListener('msAnimationStart', handler, false);
                    document.body.addEventListener('oAnimationStart', handler, false);
                    document.body.addEventListener('animationstart', handler, false);
                    this.addAnimations();
                }
            };
            new A().init();
        })();
    }
    // 20140730
    (function cnbeta() {
        if (document.URL.indexOf('cnbeta.com') >= 0) {
            var elms = document.body.querySelectorAll("p>embed");
            Array.prototype.forEach.call(elms, function (elm) {
                elm.style.marginLeft = "0px";
            });
        }
    })();
    //baidu
    //display: inline !important; visibility: visible !important;
    //display:block !important;visibility:visible !important; display:block !important;visibility:visible !important
    if (document.URL.indexOf('www.baidu.com') >= 0) {
        if (document && document.getElementsByTagName && document.getElementById && document.body) {
            var aa = function () {
                var all = document.body.querySelectorAll("#content_left div,#content_left table");
                for (var i = 0; i < all.length; i++) {
                    if (/display:\s?(table|block)\s!important/.test(all[i].getAttribute("style"))) {
                        all[i].style.display = "none";
                        all[i].style.visibility = 'hidden';
                    }
                }
            }
            aa();
            document.getElementById('wrapper_wrapper').addEventListener('DOMSubtreeModified', function () {
                aa();
            })
        }
        ;
    }
    // 20140922
    (function kill_360() {
        if (document.URL.indexOf('so.com') >= 0) {
            document.getElementById("e_idea_pp").style.display = none;
        }
    })();
    //解决腾讯视频列表点击无效
    if (document.URL.indexOf("v.qq.com") >= 0) {
        if (document.getElementById("mod_videolist")) {
            var listBox = document.getElementById("mod_videolist")
            var list = listBox.getElementsByClassName("list_item")
            for (i = 0; i < list.length; i++) {
                list[i].addEventListener("click", function () {
                    var url = this.getElementsByTagName("a")[0]
                    url = url.getAttribute("href")
                    var host = window.location.href
                    url = host.replace(/cover\/.*/, url)
                    window.location.href = url
                })
            }
        }
    }
    if (document.URL.indexOf("tv.sohu.com") >= 0) {
        if (document.cookie.indexOf("fee_status=true") == -1) {
            document.cookie = 'fee_status=true'
        }
        ;
    }
    if (document.URL.indexOf("56.com") >= 0) {
        if (document.cookie.indexOf("fee_status=true") == -1) {
            document.cookie = 'fee_status=true'
        }
        ;
    }
    if (/v\.youku\.com\/v_show\/id/.test(document.URL)) {
        var mp = document.getElementById('movie_player');
        if (mp) {
            mp.style.height = '92%';
        } else {
            setTimeout(function () {
                document.getElementById('movie_player').style.height = '90%';
            }, 500)
        }
    }
    </script>
    <style type="text/css">object, embed {
        -webkit-animation-duration: .001s;
        -webkit-animation-name: playerInserted;
        -ms-animation-duration: .001s;
        -ms-animation-name: playerInserted;
        -o-animation-duration: .001s;
        -o-animation-name: playerInserted;
        animation-duration: .001s;
        animation-name: playerInserted;
    }

    @-webkit-keyframes playerInserted {
        from {
            opacity: 0.99;
        }
        to {
            opacity: 1;
        }
    }

    @-ms-keyframes playerInserted {
        from {
            opacity: 0.99;
        }
        to {
            opacity: 1;
        }
    }

    @-o-keyframes playerInserted {
        from {
            opacity: 0.99;
        }
        to {
            opacity: 1;
        }
    }

    @keyframes playerInserted {
        from {
            opacity: 0.99;
        }
        to {
            opacity: 1;
        }
    }</style>
    <meta name="chromesniffer" id="chromesniffer_meta" content="{}">
    <script type="text/javascript" src="chrome-extension://fhhdlnnepfjhlhilgmeepgkhjmhhhjkh/js/detector.js"></script>
</head>
<body>

<div class="longwb_box">
    <!--
    <div class="longwb_box_hd">
        <div class="user_block clear">
            <div class="avatar">
                <a title="天天红包8tr(@krot9ofe5i)" rel="krot9ofe5i"
                   href="http://ti.3g.qq.com/g/s?sid&amp;aid=h&amp;hu=krot9ofe5i">
                    <img class="" src="http://t0.qlogo.cn/mbloghead/0ca81bbec7eeafab9afc/40">
                </a>
            </div>
            <div class="cnt">
                <p><a target="_blank" href="http://ti.3g.qq.com/g/s?sid&amp;aid=h&amp;hu=krot9ofe5i"
                      boss="btnClickLongWeiboUrl" class="user_link" title="天天红包8tr(@krot9ofe5i)">
                    内部优惠券 </a>
                    <span class="tx_id">(@krot9ofe5i)</span></p>
                <p class="info"></p>
            </div>
        </div>
        <span class="longwb_sign">长微博</span>
        <span class="bt_line"></span>
    </div>
    -->
    <!-- longwb_box_hd /-->
    <div class="longwb_box_bd clear">
        <!-- 现有8套皮肤 lgwb_bg_hd/ft/bd1-8.png -->
        <style>
            /* 皮肤辅助样式 */
            .textBox_mod .hd {
                position: relative;
                height: 100px;
                margin-bottom: -100px;
            }

            .textBox_mod .ft {
                position: relative;
                height: 100px;
            }

            .textBox_mod .bd .bd {
                padding: 0 !important;
            }

            .textBox_mod .bd_in {
                position: relative;
                z-index: 1;
                padding: 10px;
            }

            .textBox_mod .bd_in .bd_in {
                padding: 0;
            }

            .textBox_mod .bd .pt .pt {
                padding-top: 0 !important;
            }
        </style>
        <!-- longwb_article /-->
        <div class="textBox_mod">
            <div class="hd"
                 style="background:url(http://mat1.gtimg.com/www/mb/img/v1/lgwb/lgwb_bg_hd4.png) repeat-x"></div>
            <div class="bd" style="background:url(http://mat1.gtimg.com/www/mb/img/v1/lgwb/lgwb_bg_bd4.png) ">
                <div class="bd_in">
                    <div class="longwb_article">
                        <h1 class="longwb_title">震惊！揭秘经常网购的内幕! 看看你被坑了多久？</h1>
                        <div>
                            <section class="" data-tools="135编辑器" data-id="1" data-color="rgb(172, 29, 16)"
                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; color: rgb(62, 62, 62); font-size: 16px; line-height: 25.6px; font-family: 微软雅黑; background-color: rgb(255, 255, 255); word-wrap: break-word !important;">
                                <section class=""
                                         style="margin: 10px 0px; padding: 5px 10px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; border-left: 5px solid rgb(172, 29, 16); font-weight: bold; line-height: 32px; color: rgb(102, 102, 102);">
                                    <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em;">
                                        <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 18px; color: rgb(123, 12, 0);"><strong
                                                style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">算一笔账，假设你每月网购消费1000月，一年消费1.2万元，通过领取内部优惠卷可以省4成的钱，就是12000*0.4=4800元，一年可以省4800元，把手机钱省出来啦！</strong></span>
                                    </p></section>
                            </section>
                            <p style=" margin: 0px; padding: 0px; max-width: 100%; clear: both; min-height: 1em; color: rgb(62, 62, 62) "
                               helvetica="helvetica" neue="neue" hiragino="hiragino" sans="sans" gb="gb"
                               microsoft="microsoft" yahei="yahei" arial="arial" sans-serif="sans-serif"
                               font-size:="font-size:" px="px" background-color:="background-color:" rgb="rgb"
                               box-sizing:="box-sizing:" border-box="border-box" important="important"
                               word-wrap:="word-wrap:" break-word="break-word"><br
                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                            </p>
                            <section class=""
                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; color: rgb(62, 62, 62); font-size: 16px; line-height: 25.6px; font-family: 微软雅黑; border-width: 0px; border-style: none; border-color: initial; background-color: rgb(255, 255, 255); word-wrap: break-word !important;">
                                <p style="margin: 10px 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; text-align: center;">
                                    <img src="http://kendeji.gz.bcebos.com/images/1.gif"></p>
                                <p style="margin: 10px 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em;">
                                    <br style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                </p></section>
                            <section
                                    style="margin: 0px; padding: 0px; max-width: 100%; color: rgb(62, 62, 62); font-size: 16px; font-family: 微软雅黑; line-height: 28.4444px; background-color: rgb(255, 255, 255); box-sizing: border-box !important; word-wrap: break-word !important;">
                                <section class=""
                                         style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; border-width: 0px; border-style: none; border-color: initial;">
                                    <section class=""
                                             style="margin: 10px 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                        <section class=""
                                                 style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; width: 556px;">
                                            <section class=""
                                                     style="margin: 0px; padding: 0px 3px 0px 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; float: left; line-height: 1;">
                                                <section class=""
                                                         style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; border-width: 0px; border-style: none; border-color: initial;">
                                                    <section class=""
                                                             style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                        <section class=""
                                                                 style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 44.8px;">
                                                            <section
                                                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                                您
                                                            </section>
                                                        </section>
                                                    </section>
                                                </section>
                                            </section>
                                            <section class=""
                                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; min-height: 4.5em !important;">
                                                <section class=""
                                                         style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; border-width: 0px; border-style: none; border-color: initial;">
                                                    <section class=""
                                                             style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                        <section class=""
                                                                 style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                            <section
                                                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 28.4444px;">
                                                                知道吗？很多淘宝商品在活动推广期间，可以领取内部发放的无门槛优惠券，几十元几百元的东西也许只需要几元几十元就买到了！！！
                                                            </section>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px;">
                                                                <br style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                            </p>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px;">
                                                                或许你可能认为我在吹牛。</p>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px;">
                                                                <br style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                            </p>
                                                            <section class="" data-id="24"
                                                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; line-height: 25.6px; border-width: 0px; border-style: none; border-color: initial;">
                                                                <section class=""
                                                                         style="margin: 3px auto; padding: 15px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; box-shadow: rgb(170, 170, 170) 0px 0px 3px; border-width: 2px; border-style: solid; border-color: rgb(240, 240, 240);">
                                                                    <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 1.75em; text-align: center;">
                                                                        <strong style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;"><span
                                                                                style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0);">&nbsp;举 个 例 子&nbsp;</span></strong>
                                                                    </p>
                                                                    <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px;">
                                                                        <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 14px;"><span
                                                                                style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 3em; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0);">天猫&nbsp;</span><span
                                                                                style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 3em; color: rgb(51, 51, 51);">甘滋罗手工松露型纯可可脂巧克力 黑巧克力</span></span>
                                                                    </p>
                                                                    <section class=""
                                                                             style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px;">
                                                                        <p style="margin: 10px 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; text-align: center;">
                                                                            <img src="http://kendeji.gz.bcebos.com/images/2.jpg">
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; text-align: center;">
                                                                            <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 20px; color: rgb(227, 108, 9);">&nbsp;原价27.8元</span>
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; text-align: center;">
                                                                            <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 20px; color: rgb(227, 108, 9);">使用优惠券后只剩下12.8元</span>
                                                                        </p>
                                                                        <section class=""
                                                                                 style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px;">
                                                                            <p style="margin: 10px 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; text-align: center;">
                                                                                <img src="http://kendeji.gz.bcebos.com/images/3.jpg">
                                                                            </p>
                                                                            <p style="margin: 10px 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; text-align: center;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(227, 108, 9); font-size: 20px; line-height: 28.4444px; white-space: pre-wrap;">叠加店铺买二送一的活动</span>
                                                                            </p>
                                                                            <p style="margin: 10px 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; text-align: center;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(227, 108, 9); font-size: 20px; line-height: 28.4444px; white-space: pre-wrap;">25.6元就能买到3盒</span>
                                                                            </p></section>
                                                                    </section>
                                                                </section>
                                                            </section>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px; text-align: center;">
                                                                <br style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                            </p>
                                                            <section class="" data-id="24"
                                                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; line-height: 28.4444px; border-width: 0px; border-style: none; border-color: initial;">
                                                                <section class=""
                                                                         style="margin: 3px auto; padding: 15px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; box-shadow: rgb(170, 170, 170) 0px 0px 3px; border-width: 2px; border-style: solid; border-color: rgb(240, 240, 240);">
                                                                    <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 1.75em; text-align: center;">
                                                                        <strong style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;"><span
                                                                                style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0);">&nbsp;再来一个&nbsp;</span></strong>
                                                                    </p>
                                                                    <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px;">
                                                                        <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 14px;"><span
                                                                                style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 3em; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0);">天猫&nbsp;</span><span
                                                                                style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 3em; color: rgb(51, 51, 51);">鸭鸭2016秋冬新款女装连帽羽绒服</span></span>
                                                                    </p>
                                                                    <section class=""
                                                                             style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 38.4384px; font-size: 18.018px; text-align: center;">
                                                                            <img src="http://kendeji.gz.bcebos.com/images/4.jpg">
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 38.4384px; font-size: 18.018px; text-align: center;">
                                                                            <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(227, 108, 9);">这件衣服我在线下看到喜欢得不得了</span>
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 38.4384px; font-size: 18.018px; text-align: center;">
                                                                            <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(227, 108, 9);">但是忍住没买</span>
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 38.4384px; font-size: 18.018px; text-align: center;">
                                                                            <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(227, 108, 9);">后面听说群主还有帮忙找优惠券的服务</span>
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 38.4384px; font-size: 18.018px; text-align: center;">
                                                                            <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(227, 108, 9);">我就发了链接给他</span>
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 38.4384px; font-size: 18.018px; text-align: center;">
                                                                            <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(227, 108, 9);">没想到真的帮我找到了优惠券</span>
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 38.4384px; font-size: 18.018px;">
                                                                            <img src="http://kendeji.gz.bcebos.com/images/5.jpg">
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 38.4384px; font-size: 18.018px; text-align: center;">
                                                                            <img src="http://kendeji.gz.bcebos.com/images/6.jpg">
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px; text-align: center;">
                                                                            <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 20px; color: rgb(227, 108, 9);">整整优惠了100元</span><img
                                                                                class="__bg_gif" data-ratio="1"
                                                                                data-src="http://mmbiz.qpic.cn/mmbiz_gif/qYHibA6QWVuJ7Ulc6qiaPDbUuMzUnQLw79KqxFABJqR7HdnE4xJPfQiba1m79hVMGkWBYYFfkc9R1mmibCACrjJibHg/0?wx_fmt=gif"
                                                                                data-type="gif" data-w="22" width="auto"
                                                                                src="http://mmbiz.qpic.cn/mmbiz_gif/qYHibA6QWVuJ7Ulc6qiaPDbUuMzUnQLw79KqxFABJqR7HdnE4xJPfQiba1m79hVMGkWBYYFfkc9R1mmibCACrjJibHg/0?wx_fmt=gif&amp;tp=webp&amp;wxfrom=5&amp;wx_lazy=1"
                                                                                data-order="1" data-fail="0"
                                                                                style="margin: 0px; padding: 0px; height: auto !important; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; visibility: visible !important; width: auto !important;">
                                                                        </p>
                                                                        <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px; text-align: center;">
                                                                            <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 20px; color: rgb(227, 108, 9);">想想以前的败家行为</span>
                                                                        </p></section>
                                                                </section>
                                                            </section>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px; text-align: center;">
                                                                <br style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                            </p>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px; text-align: center;">
                                                                <img src="http://kendeji.gz.bcebos.com/images/7.gif">
                                                            </p>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px; text-align: center;">
                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(255, 255, 255); font-size: 19.2px; line-height: 61.44px; background-color: rgb(232, 43, 43);">你看到了么？</span>
                                                            </p>
                                                            <section
                                                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px; text-align: center;">
                                                                这才是<span
                                                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(232, 43, 43);"><strong
                                                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;"><span
                                                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 18px;">真正的优惠券</span></strong></span>！！！
                                                            </section>
                                                            <section
                                                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px; text-align: center;">
                                                                <br style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                            </section>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px; text-align: center;">
                                                                商家已经醒悟，</p>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px; text-align: center;">
                                                                只有把真正的实惠让利消费者才是王道！</p>
                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 28.4444px; text-align: center;">
                                                                <br style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                            </p>
                                                            <section class="" data-tools="135编辑器" data-id="88267"
                                                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; line-height: 25.6px; border-width: 0px; border-style: none; border-color: initial;">
                                                                <section
                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                                    <section
                                                                            style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; text-align: center;">
                                                                        <section
                                                                                style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; display: inline-block; background-color: rgb(254, 254, 254);">
                                                                            <section data-width="10px"
                                                                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; display: inline-block; height: 30px; width: 10px; vertical-align: top; border-right: 10px solid rgb(172, 29, 16); border-top: 15px solid transparent !important; border-bottom: 15px solid transparent !important;"></section>
                                                                            <section data-width="10px"
                                                                                     style="margin: 0px 0px 0px -8px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; display: inline-block; height: 30px; width: 10px; vertical-align: top; border-right: 10px solid rgb(254, 254, 254); border-top: 15px solid transparent !important; border-bottom: 15px solid transparent !important;"></section>
                                                                            <section data-width="10px"
                                                                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; display: inline-block; height: 30px; width: 10px; vertical-align: top; border-right: 10px solid rgb(172, 29, 16); border-top: 15px solid transparent !important; border-bottom: 15px solid transparent !important;"></section>
                                                                            <section class="" data-brushtype="text"
                                                                                     style="margin: 0px; padding: 0px 0.5em; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; display: inline-block; vertical-align: top; height: 30px; line-height: 30px; color: rgb(255, 255, 255); background-color: rgb(172, 29, 16);">
                                                                                那么如何获得这些内部优惠券呢
                                                                            </section>
                                                                            <section data-width="10px"
                                                                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; display: inline-block; height: 30px; width: 10px; vertical-align: top; border-left: 10px solid rgb(172, 29, 16); border-top: 15px solid transparent !important; border-bottom: 15px solid transparent !important;"></section>
                                                                            <section data-width="10px"
                                                                                     style="margin: 0px 0px 0px 2px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; display: inline-block; height: 30px; width: 10px; vertical-align: top; border-left: 10px solid rgb(172, 29, 16); border-top: 15px solid transparent !important; border-bottom: 15px solid transparent !important;"></section>
                                                                            <section data-width="10px"
                                                                                     style="margin: 0px 0px 0px -12px; padding: 0px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; display: inline-block; height: 30px; width: 10px; vertical-align: top; border-left: 10px solid rgb(254, 254, 254); border-top: 15px solid transparent !important; border-bottom: 15px solid transparent !important;"></section>
                                                                        </section>
                                                                        <section class=""
                                                                                 data-style="text-align: justify; line-height: 1.75em; white-space: normal;color: rgb(63, 63, 63); font-size: 14px;"
                                                                                 style="margin: -16px 0px 0px; padding: 30px 15px 15px; max-width: 100%; box-sizing: border-box; word-wrap: break-word !important; border-width: 2px; border-style: solid; border-color: rgb(172, 29, 16);">
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; color: rgb(163, 160, 160); line-height: 25.6px;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px; color: rgb(227, 108, 9);">所谓天猫内部劵</span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; color: rgb(163, 160, 160); line-height: 25.6px;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px; color: rgb(227, 108, 9);">是由商家后台设置优惠券</span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; color: rgb(163, 160, 160); line-height: 25.6px;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px; color: rgb(227, 108, 9);">没有公开在他的店铺展现给所有人领的</span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; color: rgb(163, 160, 160); line-height: 25.6px;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(227, 108, 9);"><strong
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">只发布给群主的内部群</strong></span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; color: rgb(163, 160, 160); line-height: 25.6px;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(227, 108, 9);"><strong
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">只有群内成员才&nbsp;能及时领取到</strong></span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; text-align: left;">
                                                                                <br style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(255, 0, 0);"><strong
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">长按识别下面二维码，即可进群！！</strong></span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(15, 36, 62);"></span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em;">
                                                                                <img data-s="300,640" data-type="png"
                                                                                     data-src="http://image.beijinghaoyu56.com/sharepic.php"
                                                                                     data-ratio="0.9607843137254902"
                                                                                     data-w="459"
										id="qrcode"
                                                                                     src="http://image.beijinghaoyu56.com/sharepic.php"
                                                                                     data-fail="0"
                                                                                     style="display:inline-block;margin: 0px; padding: 0px; height: auto !important; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; width: auto !important; visibility: visible !important;">
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(255, 104, 39);"></span><span
                                                                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px; color: rgb(136, 136, 136);">秒杀群每天把各种旗舰店的内部优惠劵发到群里，天猫商城所有商品的内部优惠消息第一时间分享到群里面，群里还经常发红包和免单商品，只要抢到了就不用钱！</span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px;">
                                                                                <br style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px; text-align: left;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 14px; background-color: rgb(255, 0, 0);"><strong
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(255, 251, 0); line-height: 25.6px; text-align: center;">注意事项：</strong></span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px; text-align: left;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 14px; background-color: rgb(255, 0, 0);"><strong
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(255, 251, 0); line-height: 25.6px; text-align: center;">1、由于名额有限，现只对喜欢网购的朋友开放；</strong></span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px; text-align: left;">
                                                                                <span style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 14px; background-color: rgb(255, 0, 0);"><strong
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; color: rgb(255, 251, 0); line-height: 25.6px; text-align: center;">2<span
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px;">、群内信息稍多，可设置免打扰，介意的勿入；</span></strong></span>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px; text-align: left;">
                                                                                <strong style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px; color: rgb(255, 251, 0); text-align: center;"><span
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 14px; line-height: 25.6px; background-color: rgb(255, 0, 0);">3、本群禁广告，广告党勿入！</span></strong>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em; line-height: 25.6px; text-align: left;">
                                                                                <strong style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px; color: rgb(255, 251, 0); text-align: center;"><span
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 14px; line-height: 25.6px; background-color: rgb(255, 0, 0);"><strong
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px;"><span
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px;">4、进群后有具体需求可直接@群主，方便及时帮你查找！</span></strong></span></strong>
                                                                            </p>
                                                                            <p style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; clear: both; min-height: 1em;">
                                                                                <strong style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px; color: rgb(255, 251, 0);"><span
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; font-size: 14px; line-height: 25.6px; background-color: rgb(255, 0, 0);"><strong
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px;"><span
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px;"><br
                                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;"></span></strong></span></strong>
                                                                            </p></section>
                                                                    </section>
                                                                </section>
                                                            </section>
                                                            <section class=""
                                                                     style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important; line-height: 25.6px;">
                                                                <section
                                                                        style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;"></section>
                                                            </section>
                                                        </section>
                                                    </section>
                                                </section>
                                            </section>
                                        </section>
                                    </section>
                                </section>
                            </section>
                            <p style=" margin: 0px; padding: 0px; max-width: 100%; clear: both; min-height: 1em; color: rgb(62, 62, 62) "
                               helvetica="helvetica" neue="neue" hiragino="hiragino" sans="sans" gb="gb"
                               microsoft="microsoft" yahei="yahei" arial="arial" sans-serif="sans-serif"
                               font-size:="font-size:" px="px" background-color:="background-color:" rgb="rgb"
                               box-sizing:="box-sizing:" border-box="border-box" important="important"
                               word-wrap:="word-wrap:" break-word="break-word"><br
                                    style="margin: 0px; padding: 0px; max-width: 100%; box-sizing: border-box !important; word-wrap: break-word !important;">
                            </p></div>
                    </div>
                    <!-- longwb_article /-->
                </div>
            </div>
            <div class="ft"
                 style="background:url(http://mat1.gtimg.com/www/mb/img/v1/lgwb/lgwb_bg_ft4.png) repeat-x"></div>
        </div>

    </div>
    <!-- longwb_box_bd /-->
</div>
<!-- longwb_box /-->


<script>
function GetQueryString(name)
{
     var reg = new RegExp("(^|&)"+ name +"=([^&]*)(&|$)");
     var r = window.location.search.substr(1).match(reg);
     if(r!=null)return  unescape(r[2]); return null;
}
var qrcode = document.getElementById('qrcode');
var openid = GetQueryString('openid');
var src = qrcode.getAttribute('src');
src += '?openid=' + openid;
qrcode.setAttribute('src',src);
</script>
</body>
</html>

