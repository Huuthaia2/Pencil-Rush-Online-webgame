! function () {
    "use strict";
    class e {
        constructor() {
            this.isLoad = !0, this.isLog = !1, this.pencilRotateSpeed = 70, this.lrRotateSpeed = .8, this.pencilMoveSpeed = 2.5, this.lrcucaodu = 2.5, this.pencilLRSpeed = .01, this.cameraSmoth = 3, this._failCoinNum = 20, this._winCoinNum = 400, this.videoCoin = 800, this.skinPrice = 800, this._completePictureCoin = 500, this.intensify_Coin = [
                [1, 200, 1],
                [2, 300, 1.02],
                [3, 400, 1.04],
                [4, 500, 1.06],
                [5, 600, 1.08],
                [6, 700, 1.1],
                [7, 800, 1.12],
                [8, 900, 1.14],
                [9, 1e3, 1.16],
                [10, 1100, 1.18],
                [11, 1200, 1.2],
                [12, 1300, 1.22],
                [13, 1400, 1.24],
                [14, 1500, 1.26],
                [15, 1600, 1.28],
                [16, 1700, 1.3],
                [17, 1800, 1.32],
                [18, 1900, 1.34],
                [19, 2e3, 1.36],
                [20, 2100, 1.38],
                [21, 2200, 1.4],
                [22, 2300, 1.42],
                [23, 2400, 1.44],
                [24, 2500, 1.46],
                [25, 2600, 1.48],
                [26, 2700, 1.5],
                [27, 2800, 1.52],
                [28, 2900, 1.54],
                [29, 3e3, 1.56],
                [30, 3100, 1.58],
                [31, 3200, 1.6],
                [32, 3300, 1.62],
                [33, 3400, 1.64],
                [34, 3500, 1.66],
                [35, 3600, 1.68],
                [36, 3700, 1.7],
                [37, 3800, 1.72],
                [38, 3900, 1.74],
                [39, 4e3, 1.76],
                [40, 4100, 1.78],
                [41, 4200, 1.8],
                [42, 4300, 1.82],
                [43, 4400, 1.84],
                [44, 4500, 1.86],
                [45, 4600, 1.88],
                [46, 4700, 1.9],
                [47, 4800, 1.92],
                [48, 4900, 1.94],
                [49, 5e3, 1.96],
                [50, 5100, 1.98]
            ], this.intensify_PencilLoss = [
                [1, 200, .07],
                [2, 300, .0695],
                [3, 400, .069],
                [4, 500, .0685],
                [5, 600, .068],
                [6, 700, .0675],
                [7, 800, .067],
                [8, 900, .0665],
                [9, 1e3, .066],
                [10, 1100, .0655],
                [11, 1200, .065],
                [12, 1300, .0645],
                [13, 1400, .064],
                [14, 1500, .0635],
                [15, 1600, .063],
                [16, 1700, .0625],
                [17, 1800, .062],
                [18, 1900, .0615],
                [19, 2e3, .061],
                [20, 2100, .0605],
                [21, 2200, .06],
                [22, 2300, .0595],
                [23, 2400, .059],
                [24, 2500, .0585],
                [25, 2600, .058],
                [26, 2700, .0575],
                [27, 2800, .057],
                [28, 2900, .0565],
                [29, 3e3, .056],
                [30, 3100, .0555],
                [31, 3200, .055],
                [32, 3300, .0545],
                [33, 3400, .054],
                [34, 3500, .0535],
                [35, 3600, .053],
                [36, 3700, .0525],
                [37, 3800, .052],
                [38, 3900, .0515],
                [39, 4e3, .051],
                [40, 4100, .0505],
                [41, 4200, .05],
                [42, 4300, .0495],
                [43, 4400, .049],
                [44, 4500, .0485],
                [45, 4600, .048],
                [46, 4700, .0475],
                [47, 4800, .047],
                [48, 4900, .0465],
                [49, 5e3, .046],
                [50, 5100, .0455]
            ], this.intensify_PencilNum = [
                [1, 200, 1],
                [2, 300, 2],
                [3, 400, 3],
                [4, 500, 4],
                [5, 600, 5],
                [6, 700, 6],
                [7, 800, 7],
                [8, 900, 8],
                [9, 1e3, 9],
                [10, 1100, 10],
                [11, 1200, 11],
                [12, 1300, 12],
                [13, 1400, 13],
                [14, 1500, 14],
                [15, 1600, 15],
                [16, 1700, 16],
                [17, 1800, 17],
                [18, 1900, 18],
                [19, 2e3, 19],
                [20, 2100, 20],
                [21, 2200, 21],
                [22, 2300, 22],
                [23, 2400, 23],
                [24, 2500, 24],
                [25, 2600, 25],
                [26, 2700, 26],
                [27, 2800, 27],
                [28, 2900, 28],
                [29, 3e3, 29],
                [30, 3100, 30],
                [31, 3200, 31],
                [32, 3300, 32],
                [33, 3400, 33],
                [34, 3500, 34],
                [35, 3600, 35],
                [36, 3700, 36],
                [37, 3800, 37],
                [38, 3900, 38],
                [39, 4e3, 39],
                [40, 4100, 40],
                [41, 4200, 41],
                [42, 4300, 42],
                [43, 4400, 43],
                [44, 4500, 44],
                [45, 4600, 45],
                [46, 4700, 46],
                [47, 4800, 47],
                [48, 4900, 48],
                [49, 5e3, 49],
                [50, 5100, 50]
            ], this.maxPicture = 30, this.texture = {
                1: "21_tg_cbklh.png",
                2: "22_tg_cbklh.png",
                3: "23_tg_cbklh.png",
                4: "24_tg_cbklh.png",
                5: "25_tg_cbklh.png",
                6: "26_tg_cbklh.png",
                7: "27_tg_cbklh.png",
                8: "28_tg_cbklh.png",
                9: "29_tg_cbklh.png",
                10: "30_tg_cbklh.png",
                11: "9_tg_cbklh.png",
                12: "10_tg_cbklh.png",
                13: "11_tg_cbklh.png",
                14: "12_tg_cbklh.png",
                15: "13_tg_cbklh.png",
                16: "14_tg_cbklh.png",
                17: "15_tg_cbklh.png",
                18: "16_tg_cbklh.png",
                19: "17_tg_cbklh.png",
                20: "18_tg_cbklh.png",
                21: "19_tg_cbklh.png",
                22: "20_tg_cbklh.png",
                23: "1_tg_cbklh.png",
                24: "2_tg_cbklh.png",
                25: "3_tg_cbklh.png",
                26: "4_tg_cbklh.png",
                27: "5_tg_cbklh.png",
                28: "6_tg_cbklh.png",
                29: "7_tg_cbklh.png",
                30: "8_tg_cbklh.png"
            }, this.moheNum = 40, this.coinNum = 0, this.currentLevel = 1, this.pencilNum = 2, this.picturePoint = 6, this.PictureData = {
                currentPictureID: 1,
                currentRandomArr: -1,
                currentPictureProgress: 0
            }, this.album = {
                haved: [],
                progress: []
            }, this.intensify = {
                pencilNum: 1,
                coinIntensify: 1,
                pencilLossIntensify: 1
            }, this.Skin = {
                mySkin: -1
            }, this.isNewUser = !0, this.isHaveNewPicture = !1, this.realLevel = 1, this.gameNum = 0, this.GamePointReport = !0;
        }
        static get Instance() {
            return null == this._instance && (this._instance = new e()), this._instance;
        }
        get failCoinNum() {
            return Math.floor(this._failCoinNum * this.intensify_Coin[this.intensify.coinIntensify - 1][2]);
        }
        get winCoinNum() {
            return Math.floor(this._winCoinNum * this.intensify_Coin[this.intensify.coinIntensify - 1][2]);
        }
        get completePictureCoin() {
            return Math.floor(this._completePictureCoin * this.intensify_Coin[this.intensify.coinIntensify - 1][2]);
        }
    }
    e._instance = null;
    let t = Laya.Shader3D,
        n = Laya.VertexMesh;
    class a extends Laya.Material {
        constructor() {
            super(), this.setShaderName("UnlitGround");
        }
        static initShader() {
            var e = {
                a_Position: n.MESH_POSITION0,
                a_Texcoord0: n.MESH_TEXTURECOORDINATE0,
                a_Texcoord1: n.MESH_TEXTURECOORDINATE1,
                a_MvpMatrix: n.MESH_MVPMATRIX_ROW0
            },
                a = {
                    u_DiffuseTexture: t.PERIOD_MATERIAL,
                    u_NoiseTex: t.PERIOD_MATERIAL,
                    u_Time: t.PERIOD_SCENE,
                    u_MvpMatrix: t.PERIOD_SPRITE
                },
                i = {
                    s_Cull: t.RENDER_STATE_CULL,
                    s_Blend: t.RENDER_STATE_BLEND,
                    s_BlendSrc: t.RENDER_STATE_BLEND_SRC,
                    s_BlendDst: t.RENDER_STATE_BLEND_DST,
                    s_DepthTest: t.RENDER_STATE_DEPTH_TEST,
                    s_DepthWrite: t.RENDER_STATE_DEPTH_WRITE
                },
                s = t.add("UnlitGround", null, null, !0),
                o = new Laya.SubShader(e, a);
            s.addSubShader(o), o.addShaderPass('\n        #include "Lighting.glsl";\n        varying vec2 v_Texcoord0;\n        varying vec4 i_Position;\n        attribute vec2 a_Texcoord0;\n        attribute vec4 a_Position;\n        #ifdef GPU_INSTANCE\n            attribute mat4 a_MvpMatrix;\n        #else\n            uniform mat4 u_MvpMatrix;\n        #endif\n\n        \n        uniform float u_Time;\n\n        void main() {\n            vec4 position;\n            position=a_Position;\n\n            \n\n            #ifdef GPU_INSTANCE\n                gl_Position = a_MvpMatrix * position;\n            #else\n                gl_Position = u_MvpMatrix * position;\n            #endif\n    \n\n            v_Texcoord0=a_Texcoord0;\n\n            gl_Position=remapGLPositionZ(gl_Position);\n        }\n        ', "\n            #if defined(GL_FRAGMENT_PRECISION_HIGH)\n            precision highp float;\n            #else\n                precision mediump float;\n            #endif\n            \n            varying vec2 v_Texcoord0;\n\n            varying vec4 i_Position;\n\n            uniform sampler2D u_DiffuseTexture;\n\t\t\t#ifdef FOG\n\t\t\tuniform float u_FogStart;\n\t\t\tuniform float u_FogRange;\n\t\t\t#ifdef ADDTIVEFOG\n\t\t\t#else\n\t\t\t\tuniform vec3 u_FogColor;\n\t\t\t#endif\n\t\t\t#endif\n            void main()\n            {\n                vec4 color ;\n                if(v_Texcoord0.x < 0.0)\n                {\n                    color = vec4(1.0,1.0,1.0,1.0);\n                }\n                else\n                {\n                    color = texture2D(u_DiffuseTexture,v_Texcoord0);\n                }\n                \n                gl_FragColor = color;\n\n\t\t\t\t#ifdef FOG\n\t\t\t\tfloat lerpFact = clamp((1.0 / gl_FragCoord.w - u_FogStart) / u_FogRange, 0.0, 1.0);\n\t\t\t\t#ifdef ADDTIVEFOG\n\t\t\t\t\tgl_FragColor.rgb = mix(gl_FragColor.rgb, vec3(0.0), lerpFact);\n\t\t\t\t#else\n\t\t\t\t\tgl_FragColor.rgb = mix(gl_FragColor.rgb, u_FogColor, lerpFact);\n\t\t\t\t#endif\n\t\t\t\t#endif\n            }\n        ", i);
        }
        set albedoTexture(e) {
            this._shaderValues.setTexture(a.ALBEDOTEXTURE, e);
        }
        set noiseTex(e) {
            this._shaderValues.setTexture(a.NOISE_TEX, e);
        }
        set Radius(e) {
            this._shaderValues.setNumber(a.RADIUS, e);
        }
        set Width(e) {
            this._shaderValues.setNumber(a.WIDTH, e);
        }
        set albedoColor(e) {
            this._shaderValues.setVector(a.ALBEDOCOLOR, e);
        }
        set renderMode(e) {
            switch (e) {
                case a.RENDERMODE_OPAQUE:
                    this.alphaTest = !1, this.renderQueue = Laya.Material.RENDERQUEUE_OPAQUE, this.depthWrite = !0, this.cull = Laya.RenderState.CULL_BACK, this.blend = Laya.RenderState.BLEND_DISABLE, this.depthTest = Laya.RenderState.DEPTHTEST_LESS;
                    break;
                case a.RENDERMODE_CUTOUT:
                    this.renderQueue = Laya.Material.RENDERQUEUE_ALPHATEST, this.alphaTest = !0, this.depthWrite = !0, this.cull = Laya.RenderState.CULL_BACK, this.blend = Laya.RenderState.BLEND_DISABLE, this.depthTest = Laya.RenderState.DEPTHTEST_LESS;
                    break;
                case a.RENDERMODE_TRANSPARENT:
                    this.renderQueue = Laya.Material.RENDERQUEUE_TRANSPARENT, this.alphaTest = !1, this.depthWrite = !1, this.cull = Laya.RenderState.CULL_BACK, this.blend = Laya.RenderState.BLEND_ENABLE_ALL, this.blendSrc = Laya.RenderState.BLENDPARAM_SRC_ALPHA, this.blendDst = Laya.RenderState.BLENDPARAM_ONE_MINUS_SRC_ALPHA, this.depthTest = Laya.RenderState.DEPTHTEST_LESS;
                    break;
                default:
                    throw new Error("UnlitGround : renderMode value error.");
            }
        }
        get depthWrite() {
            return this._shaderValues.getBool(a.DEPTH_WRITE);
        }
        set depthWrite(e) {
            this._shaderValues.setBool(a.DEPTH_WRITE, e);
        }
        get cull() {
            return this._shaderValues.getInt(a.CULL);
        }
        set cull(e) {
            this._shaderValues.setInt(a.CULL, e);
        }
        get blend() {
            return this._shaderValues.getInt(a.BLEND);
        }
        set blend(e) {
            this._shaderValues.setInt(a.BLEND, e);
        }
        get blendSrc() {
            return this._shaderValues.getInt(a.BLEND_SRC);
        }
        set blendSrc(e) {
            this._shaderValues.setInt(a.BLEND_SRC, e);
        }
        get blendDst() {
            return this._shaderValues.getInt(a.BLEND_DST);
        }
        set blendDst(e) {
            this._shaderValues.setInt(a.BLEND_DST, e);
        }
        get depthTest() {
            return this._shaderValues.getInt(a.DEPTH_TEST);
        }
        set depthTest(e) {
            this._shaderValues.setInt(a.DEPTH_TEST, e);
        }
    }
    var i;
    a.RENDERMODE_OPAQUE = 0, a.RENDERMODE_CUTOUT = 1, a.RENDERMODE_TRANSPARENT = 2, a.RENDERMODE_ADDTIVE = 3, a.ALBEDOTEXTURE = t.propertyNameToID("u_DiffuseTexture"), a.NOISE_TEX = t.propertyNameToID("u_NoiseTex"), a.RADIUS = t.propertyNameToID("u_Radius"), a.WIDTH = t.propertyNameToID("u_Width"), a.CULL = t.propertyNameToID("s_Cull"), a.BLEND = t.propertyNameToID("s_Blend"), a.BLEND_SRC = t.propertyNameToID("s_BlendSrc"), a.BLEND_DST = t.propertyNameToID("s_BlendDst"), a.DEPTH_TEST = t.propertyNameToID("s_DepthTest"), a.DEPTH_WRITE = t.propertyNameToID("s_DepthWrite"), a.ALBEDOCOLOR = t.propertyNameToID("u_AlbedoColor"),
        function (e) {
            e.MathTool = class {
                static disruptedArray(e) {
                    let t = e.length;
                    for (let n = 0; n < t - 1; n++) {
                        let a = parseInt((Math.random() * (t - n)).toString()),
                            i = e[a];
                        e[a] = e[t - n - 1], e[t - n - 1] = i;
                    }
                    return e;
                }
                static creatNumberArray(e, t) {
                    if (e >= t) return void console.error("min大于等于max");
                    let n = new Array();
                    e = Math.floor(e), t = Math.floor(t);
                    for (let a = e; a < t + 1; a++) n.push(a);
                    return n;
                }
                static getRandomNum(e, t) {
                    return Math.random() * (t - e) + e;
                }
                static getRandomInt(e, t = 0) {
                    return Math.floor(Math.random() * (e - t) + t);
                }
                static getDifferentRandomInt(e, t = 0, a = 1) {
                    let i = [],
                        s = new n();
                    for (let n = t; n < e; n++) s.add(n);
                    for (let e = 0; e < a; e++) {
                        let e = Math.floor(Math.random() * s.size),
                            t = s.get(e);
                        i.push(t), s.remove(e);
                    }
                    return i;
                }
                static getDifferentRandomIntInterval(e, t, n) {
                    let a = [],
                        i = [],
                        s = n;
                    for (let a = t; a < e; a++) s == n && (s = 0, i.push(a)), s++;
                    let o = this.getDifferentRandomInt(i.length, 0, i.length);
                    for (let e = 0; e < i.length; e++) a.push(i[o[e]]);
                    let r = [];
                    for (let t = 0; t < a.length; t++)
                        for (let i = 0; i < n; i++) a[t] + i < e && r.push(a[t] + i);
                    return r;
                }
            };
            e.AnimationTool = class {
                static moveTo3d(e, t, n, a = !1, i = null) {
                    let s = new Laya.Vector3(),
                        o = {
                            x: (s = a ? e.transform.localPosition.clone() : e.transform.position.clone()).x,
                            y: s.y,
                            z: s.z
                        },
                        r = {
                            x: t.x,
                            y: t.y,
                            z: t.z,
                            update: new Laya.Handler(this, function () {
                                e.destroyed ? l.clear() : a ? e.transform.localPosition = new Laya.Vector3(o.x, o.y, o.z) : e.transform.position = new Laya.Vector3(o.x, o.y, o.z);
                            })
                        },
                        l = Laya.Tween.to(o, r, n, Laya.Ease.linearIn, Laya.Handler.create(this, function () {
                            l.clear(), i && i.run();
                        }));
                }
                static creatAndMoveTo3d(e, t, n, a, i, s = !1, o = !0) {
                    let r = Laya.Sprite3D.instantiate(e, t, !1, n),
                        l = r.transform.position,
                        c = {
                            x: l.x,
                            y: l.y,
                            z: l.z
                        },
                        h = {
                            x: a.x,
                            y: a.y,
                            z: a.z,
                            update: new Laya.Handler(this, function () {
                                r.destroyed ? d.clear() : s ? r.transform.localPosition = new Laya.Vector3(c.x, c.y, c.z) : r.transform.position = new Laya.Vector3(c.x, c.y, c.z);
                            })
                        },
                        d = Laya.Tween.to(c, h, i, Laya.Ease.linearIn, Laya.Handler.create(this, function () {
                            if (o) {
                                if (r.destroyed) return;
                                r.destroy(!0);
                            }
                        }));
                }
                static matAni(e, t, n = 0) {
                    let a = e.meshRenderer.material,
                        i = a._Color.clone(),
                        s = !1,
                        o = function () {
                            e.destroyed ? Laya.timer.clearAll(e) : (s ? (a._Color = t, s = !1) : (a._Color = i, s = !0), console.log("播放材质动画"));
                        };
                    0 == n ? a._Color = t : Laya.timer.loop(n, e, o);
                }
            };
            e.LayaExpand = class {
                static Scene3DLoad(e, t, n) {
                    Laya.loader.create(e, t, n);
                }
                static Sprite3DLoad(e, t, n) {
                    Laya.loader.create(e, t, n);
                }
            };
            class t extends Laya.EventDispatcher {
                constructor() {
                    super();
                }
                static get Instance() {
                    return null == this._instance && (this._instance = new t()), this._instance;
                }
            }
            t._instance = null, e.EventMgr = t;
            e.Script3D = class extends Laya.Script3D {
                onAwake() {
                    this.gameObject = this.owner, this.transform = this.gameObject.transform;
                }
            };
            e.Vector3 = class {
                static cross(e, t) {
                    let n = new Laya.Vector3();
                    return Laya.Vector3.cross(e, t, n), n;
                }
                static getAngle(e, t) {
                    e instanceof Laya.Vector3 || (e = new Laya.Vector3(e.x, e.y, 0), t = new Laya.Vector3(t.x, t.y, 0));
                    let n = 0,
                        a = new Laya.Vector3(),
                        i = new Laya.Vector3();
                    Laya.Vector3.normalize(e, a), Laya.Vector3.normalize(t, i);
                    let s = Laya.Vector3.dot(a, i);
                    return n = Math.acos(s) * (180 / Math.PI), Math.floor(n);
                }
                static getNormal(e, t, n = !1) {
                    let a = new Laya.Vector3();
                    if (Laya.Vector3.cross(e, t, a), n) {
                        let e = new Laya.Vector3();
                        return Laya.Vector3.normalize(a, e), e;
                    }
                    return a;
                }
                static subtract(e, t) {
                    let n = new Laya.Vector3();
                    return Laya.Vector3.subtract(e, t, n), n;
                }
                static multiply(e, t) {
                    let n = new Laya.Vector3();
                    return n.setValue(e.x * t, e.y * t, e.z * t), n;
                }
                static add(e, t) {
                    let n = new Laya.Vector3();
                    return Laya.Vector3.add(e, t, n), n;
                }
            };
            class n {
                constructor() {
                    this.value = [];
                }
                add(e) {
                    return this.value.push(e);
                }
                get size() {
                    return this.value.length;
                }
                get(e) {
                    return this.value[e];
                }
                remove(e) {
                    return this.value.splice(e, 1), this.value;
                }
                indenOf(e) {
                    return this.value.indexOf(e);
                }
                removeAll() {
                    return this.value = [];
                }
                constains(e) {
                    for (var t in this.value)
                        if (e == this.value[t]) return !0;
                    return !1;
                }
                toString() {
                    return this.value.toString();
                }
            }
            e.List = n;
            e.String = class {
                static slice(e, t, n = 0) {
                    let a = e;
                    return a = a.length <= t ? e : e.slice(n, t);
                }
            };
            e.Platform = class {
                static getAndroidOrIOS(e = "windows") {
                    if (Laya.Browser.onMiniGame) {
                        let e = Laya.Browser.window.wx.getSystemInfoSync();
                        if ("ios" == e.platform) return "ios";
                        if ("android" == e.platform) return "android";
                        if ("devtools" == e.platform) return "devtools";
                    } else {
                        let e = navigator.userAgent,
                            t = e.indexOf("Android") > -1 || e.indexOf("Adr") > -1,
                            n = !!e.match(/\(i[^;]+;( U;)? CPU.+Mac OS X/);
                        if (t) return "android";
                        if (n) return "ios";
                    }
                    return e;
                }
                static vibration(e = !1) {
                    if (Laya.Browser.onMiniGame) e ? Laya.Browser.window.wx.vibrateLong() : Laya.Browser.window.wx.vibrateShort();
                    else if (Laya.Browser.onVVMiniGame) e ? Laya.Browser.window.qg.vibrateLong(null) : Laya.Browser.window.qg.vibrateShort(null);
                    else if (Laya.Browser.onQGMiniGame) e ? Laya.Browser.window.qg.vibrateLong() : Laya.Browser.window.qg.vibrateShort();
                    else {
                        if (!navigator.vibrate) return;
                        navigator.vibrate([200, 100, 200]);
                    }
                }
            };
            e.Material = class extends Laya.Material { };
        }(i || (i = {}));
    class s {
        constructor() {
            this.Scene3D = null, this.Player = null, this.Camera = null, this.pre_pencil = null, this.pre_picture = null, this.currentPicture = null, this.current_pencil_case = null, this.pre_painting = null, this.pre_specialPencil = null, this.pictureMat = null, this.particleRoot = null, this.currentLevelSp = null, this.directionalLight = null, this.Bg = null;
        }
        static get Instance() {
            return null == this._instance && (this._instance = new s()), this._instance;
        }
    }
    s._instance = null;
    class o {
        constructor() {
            this.isDown = !1, this.mouseX = 0, this.mouseY = 0, this.dataMouseX = 0, this.dataMouseY = 0, this.dataMouseX1 = 0, this.init();
        }
        static getInstance() {
            return null == this.instance && (this.instance = new o()), this.instance;
        }
        init() {
            Laya.stage.on(Laya.Event.MOUSE_DOWN, this, this.MouseDown), Laya.stage.on(Laya.Event.MOUSE_UP, this, this.MouseUp), Laya.stage.on(Laya.Event.MOUSE_OUT, this, this.MouseUp), Laya.stage.on(Laya.Event.BLUR, this, this.MouseUp), Laya.stage.on(Laya.Event.MOUSE_MOVE, this, this.MouseMove);
        }
        MouseDown() {
            this.isDown = !0, this.mouseX = Laya.MouseManager.instance.mouseX, this.mouseY = Laya.MouseManager.instance.mouseY;
        }
        MouseUp() {
            console.log(1111111111)
            this.isDown = !1, this.dataMouseX = 0, this.dataMouseY = 0;
        }
        MouseMove() {
            this.isDown && (this.dataMouseX = Laya.MouseManager.instance.mouseX - this.mouseX, this.dataMouseX1 = Laya.MouseManager.instance.mouseX - this.mouseX, this.dataMouseY = Laya.MouseManager.instance.mouseY - this.mouseY, this.mouseX = Laya.MouseManager.instance.mouseX, this.mouseY = Laya.MouseManager.instance.mouseX);
        }
    }
    o.instance = null;
    var r, l = {
        Scene3DUrl: "res/UnityScene/Scene/Conventional/MainScene.ls",
        pencilUrl: "res/UnityScene/Prefab/Conventional/Pencils.lh",
        particleUrl: "res/UnityScene/Prefab/Conventional/Particle.lh",
        pictureUrl: "res/UnityScene/Prefab/Conventional/picture.lh",
        painting: "res/UnityScene/Prefab/Conventional/painting.lh"
    },
        c = {
            LobbyScene: "Views/LobbyScene.scene",
            GameScene: "Views/GameScene.scene",
            FailScene: "Views/FailScene.scene",
            WinScene: "Views/WinScene.scene",
            OpenPencilBoxScene: "Views/OpenPencilBoxScene.scene",
            PictureScene: "Views/PictureScene.scene",
            SkinScene: "Views/SkinScene.scene",
            SpecialSkinScene: "Views/SpecialSkinScene.scene"
        };
    ! function (e) {
        e.LoadingScene = class extends Laya.Script {
            constructor() {
                super(...arguments), this.background = null, this.progressBarBG = null, this.progressBar = null, this.bottom = null, this.parent = null, this.loadIndex = 5;
            }
            onAwake() {
                this.parent = this.owner.parent, this.parent.height = Laya.stage.height, this.background && (this.background.height = Laya.stage.height), this.progressBarBG && this.progressBar && (this.progressBar.pivotX = 0, this.progressBar.pivotY = 0, this.progressBar.x = (this.parent.width - this.progressBar.width) / 2, this.progressBarBG.pivotX = 0, this.progressBarBG.pivotY = 0, this.progressBarBG.x = (this.parent.width - this.progressBar.width) / 2, null != this.bottom ? (this.progressBarBG.y = this.parent.height - this.progressBarBG.height - this.bottom, this.progressBar.y = this.parent.height - this.progressBar.height - this.bottom) : this.progressBar.y = this.progressBarBG.y, this.progressBarMask = new Laya.Panel(), this.progressBarMask.bgColor = "#000000", this.progressBar.mask = this.progressBarMask, this.progressBarMask.width = this.progressBar.width, this.progressBarMask.height = this.progressBar.height, this.progressBarMask.pos(0, 0), this.progressBarMask.scaleX = .1), Laya.Tween.to(this.progressBarMask, {
                    scaleX: .98
                }, 2e3, Laya.Ease.quadIn, Laya.Handler.create(this, function () {
                    this.loadIndex--;
                })), Laya.timer.frameLoop(1, this, this.update);
            }
            onLoad() {
                i.LayaExpand.Scene3DLoad(l.Scene3DUrl, Laya.Handler.create(this, this.loadSceneComplete));
            }
            loadSceneComplete(e) {
                let t = this;
                s.Instance.directionalLight = e.getChildByName("Directional Light"), s.Instance.Scene3D = e, s.Instance.Camera = e.getChildByName("Main Camera"), Laya.stage.addChildAt(s.Instance.Scene3D, 0), Laya.Sprite3D.load(l.particleUrl, Laya.Handler.create(this, function (e) {
                    s.Instance.particleRoot = e, t.loadIndex--;
                })), Laya.Sprite3D.load(l.painting, Laya.Handler.create(this, function (e) {
                    s.Instance.pre_painting = e, t.loadIndex--;
                })), Laya.Sprite3D.load(l.pictureUrl, Laya.Handler.create(this, function (e) {
                    s.Instance.pre_picture = e, t.loadIndex--, N.Instance.loadLevel(Laya.Handler.create(this, function () {
                        Laya.Sprite3D.load(l.pencilUrl, Laya.Handler.create(t, function (e) {
                            s.Instance.pre_pencil = e.getChildByName("pencil"), s.Instance.pre_specialPencil = e.getChildByName("specialPencil"), t.loadIndex--;
                        }));
                    }));
                }));
            }
            onLoadCompleteOpen() {
                platform.getInstance().yadstartup("Pencil-Rush-Online", () => {
                    Laya.SoundManager.muted = Laya.LocalStorage.getItem("Pencil-Rush-Online-musicState") ? JSON.parse(Laya.LocalStorage.getItem("Pencil-Rush-Online-musicState")) : false;
                    L.getInstance().playerBGM(), N.Instance.updateBG();
                    Laya.Scene.open(c.LobbyScene);
                })
            }
            update() {
                this.loadIndex <= 0 && (this.onLoadCompleteOpen(), Laya.timer.clearAll(this));
            }
        };
    }(r || (r = {}));
    class h {
        constructor() {
            this.isPlaying = !1, this.isplay = !1;
        }
        static getInstance() {
            return null == this.instance && (this.instance = new h()), this.instance;
        }
        playSound(e) {
            Laya.loader.load("res/pkg/Sounds/" + e + ".mp3", Laya.Handler.create(this, () => {
                this.sound = Laya.SoundManager.playSound("res/pkg/Sounds/" + e + ".mp3");
            }))
        }
        playerBGM() {
            Laya.loader.load("res/pkg/Sounds/bgm.mp3", Laya.Handler.create(this, () => {
                this.s = Laya.SoundManager.playMusic("res/pkg/Sounds/bgm.mp3", 0);
            }))
        }
        recoverBGM() {
            this.s && this.s.resume();
        }
        stopBGM() {
            this.s && this.s.pause();
        }
        init() { }
        playerFoot() {
            let e = this;
            Laya.loader.load("res/pkg/Sounds/footstep.mp3", Laya.Handler.create(this, () => {
                this.isplay || (this.isplay = !0, this.jiaobu = Laya.SoundManager.playSound("res/pkg/Sounds/footstep.mp3"), this.jiaobu.completeHandler = Laya.Handler.create(this, function () {
                    e.isplay = !1;
                }));
            }));
        }
    }
    h.instance = null;
    class d {
        constructor() { }
        static getInstance() {
            return null == d.instance && (d.instance = new d()), d.instance;
        }
        get(e, t, n) {
            let a = new Laya.HttpRequest();
            a.http.timeout = 7e3, a.once(Laya.Event.COMPLETE, this, e => {
                n.apply(t, [{
                    state: 200,
                    data: JSON.parse(a.data)
                }]);
            }), a.once(Laya.Event.ERROR, this, e => {
                n.apply(t, [{
                    state: 500,
                    msg: e
                }]);
            }), a.http.ontimeout = function () {
                console.log("http timeout test: timeout"), n.apply(t, [{
                    state: 408,
                    msg: "timeout"
                }]);
            }
        }
        post(e, t, n, a, i) {
            let s = new Laya.HttpRequest();
            s.http.timeout = 7e3, s.once(Laya.Event.COMPLETE, this, e => {
                i.apply(a, [{
                    state: 200,
                    data: JSON.parse(s.data)
                }]);
            }), s.once(Laya.Event.ERROR, this, e => {
                i.apply(a, [{
                    state: 500,
                    msg: e
                }]);
            }), s.http.ontimeout = function () {
                console.log("http timeout test: timeout"), i.apply(a, [{
                    state: 408,
                    msg: "timeout"
                }]);
            }
        }
        sortObject(e) {
            return Object.keys(e).sort().reduce(function (t, n) {
                return t[n] = e[n], t;
            }, {});
        }
        b64_hmac_sha1(e, t, n, a) {
            function _f(e, t, n, a) {
                return e < 20 ? t & n | ~t & a : e < 40 ? t ^ n ^ a : e < 60 ? t & n | t & a | n & a : t ^ n ^ a;
            }

            function _k(e) {
                return e < 20 ? 1518500249 : e < 40 ? 1859775393 : e < 60 ? -1894007588 : -899497514;
            }

            function _s(e, t) {
                var n = (65535 & e) + (65535 & t);
                return (e >> 16) + (t >> 16) + (n >> 16) << 16 | 65535 & n;
            }

            function _r(e, t) {
                return e << t | e >>> 32 - t;
            }

            function _c(e, t) {
                e[t >> 5] |= 128 << 24 - t % 32, e[15 + (t + 64 >> 9 << 4)] = t;
                for (var n = [80], a = 1732584193, i = -271733879, s = -1732584194, o = 271733878, r = -1009589776, l = 0; l < e.length; l += 16) {
                    for (var c = a, h = i, d = s, u = o, g = r, y = 0; y < 80; y++) {
                        n[y] = y < 16 ? e[l + y] : _r(n[y - 3] ^ n[y - 8] ^ n[y - 14] ^ n[y - 16], 1);
                        var p = _s(_s(_r(a, 5), _f(y, i, s, o)), _s(_s(r, n[y]), _k(y)));
                        r = o, o = s, s = _r(i, 30), i = a, a = p;
                    }
                    a = _s(a, c), i = _s(i, h), s = _s(s, d), o = _s(o, u), r = _s(r, g);
                }
                return [a, i, s, o, r];
            }

            function _b(e) {
                for (var t = [], n = (1 << a) - 1, i = 0; i < e.length * a; i += a) t[i >> 5] |= (e.charCodeAt(i / 8) & n) << 32 - a - i % 32;
                return t;
            }
            return n || (n = "="), a || (a = 8),
                function (e, t) {
                    return function (e) {
                        for (var t = "", a = 0; a < 4 * e.length; a += 3)
                            for (var i = (e[a >> 2] >> 8 * (3 - a % 4) & 255) << 16 | (e[a + 1 >> 2] >> 8 * (3 - (a + 1) % 4) & 255) << 8 | e[a + 2 >> 2] >> 8 * (3 - (a + 2) % 4) & 255, s = 0; s < 4; s++) 8 * a + 6 * s > 32 * e.length ? t += n : t += "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/".charAt(i >> 6 * (3 - s) & 63);
                        return t;
                    }(function (e, t) {
                        var n = _b(e);
                        n.length > 16 && (n = _c(n, e.length * a));
                        for (var i = [16], s = [16], o = 0; o < 16; o++) i[o] = 909522486 ^ n[o], s[o] = 1549556828 ^ n[o];
                        var r = _c(i.concat(_b(t)), 512 + t.length * a);
                        return _c(s.concat(r), 672);
                    }(e, t));
                }(e, t);
        }
        objToUrl(e) {
            let t = [];
            for (let n in e) e.hasOwnProperty(n) && t.push(n + "=" + e[n]);
            return t.join("&");
        }
    }
    d.instance = null;
    var u = d.getInstance();
    class g {
        constructor() {
            this.gameName = "BigHunter", this.appid = "105460318", this.channel = "vivo_kyx_BigHunter", this.version = "2", this.packName = "com.lechang.BigHunter.vivominigame", this.openId = "123", this.isNewUser = !0, this.xxNum = 0, this.bannerAd = null, this.videoAd = null, this.time = -100, this.nativeAd = null, this.adId = null, this.nativeCurrentAdList = null, this.gameNum = 0, this.lc_adtanchu = 0, this.setting = {
                Lc_ADClickTouchType: 0,
                Lc_ADClickTouchTypeN: 0,
                Lc_AutoVideoGuide: 0,
                Lc_AutoAddDesk: 0,
                Lc_ADYuanSheng_SkillShow: 0,
                Lc_ADVideo_SkillUse: 0,
                Lc_ADYuanSheng_SkillShow2: 1,
                Lc_Kuangdian: 0
            };
        }
        static getInstance() {
            return null == this.instance && (this.instance = new g()), this.instance;
        }
        init() {
            console.log("初始化vivo广告插件");
            let e = this;
            this.getSetting(function () {
                let t = Math.floor(Date.now() / 864e5),
                    n = Laya.LocalStorage.getJSON("XXnum");
                n ? n.day != t ? e.xxNum = e.setting.Lc_ADClickTouchTypeN : e.xxNum = n.index : (e.xxNum = e.setting.Lc_ADClickTouchTypeN, Laya.LocalStorage.setJSON("XXnum", {
                    day: t,
                    index: e.xxNum
                })), console.log("误触次数", e.xxNum);
            }), Laya.Browser.onVVMiniGame && this.login(), Laya.LocalStorage.getItem(this.gameName + "isNewUser") ? (Laya.LocalStorage.setItem(this.gameName + "isNewUser", "1"), this.isNewUser = !1, this.lc_adtanchu = 0) : (this.isNewUser = !0, this.lc_adtanchu = 1);
        }
        login() { }
        creatAndShowBanner(e) {
            e || (e = "d116f46231184a8caea06d5efa996e92"), this.bannerAd && this.bannerAd.destroy();
            let t = Laya.Browser.window.qg;
            this.bannerAd = t.createBannerAd({
                adUnitId: e
            }), null != this.bannerAd && (this.bannerAd.show().then(() => {
                console.log("banner广告展示完成");
            }).catch(e => {
                console.log("banner广告展示失败", JSON.stringify(e));
            }), this.bannerAd.onError(e => {
                console.log("banner展示出错:", e);
            }));
        }
        hideBanner() {
            this.bannerAd && (console.log("隐藏banner"), this.bannerAd.hide());
        }
        showBanner() {
            this.bannerAd && (console.log("展示banner"), this.bannerAd.show());
        }
        showToast(e) {
            Laya.Browser.window.qg.showToast({
                title: e,
                icon: "none",
                duration: 2e3
            });
        }
        showVideo(e, t, n) {
            e || (e = "d84dd041fb7d4d4ba66ebd8c16cb63f1");
            let a = Laya.Browser.window.qg;
            Laya.SoundManager.stopAll(), Laya.timer.pause();
            var i = function () {
                t && t();
            },
                s = this;
            if (s.videoAd) {
                let e = s.videoAd.load();
                e && e.catch(e => {
                    a.showToast({
                        message: "视频加载失败，请稍后再试"
                    }), console.log(e), Laya.timer.resume();
                }), s.videoAd.offClose(), s.videoAd.onClose(e => {
                    Laya.timer.resume(), Date.now() - s.time > 100 && (s.time = Date.now(), e.isEnded ? t && i() : n && "function" == typeof n && n());
                });
            } else s.videoAd = a.createRewardedVideoAd({
                posId: e
            }), console.log("创建激励视频"), s.videoAd.onLoad(() => {
                let e = s.videoAd.show();
                e && e.catch(e => {
                    a.showToast({
                        message: "视频加载失败，请稍后再试"
                    }), console.log(e), Laya.timer.resume();
                });
            }), s.videoAd.onError(e => {
                a.showToast({
                    message: "视频加载失败，请稍后再试"
                }), console.log(e), Laya.timer.resume();
            }), s.videoAd.offClose(), s.videoAd.onClose(e => {
                Date.now() - s.time > 100 && (s.time = Date.now(), Laya.timer.resume(), e.isEnded ? t && "function" == typeof t && i() : n && "function" == typeof n && n());
            });
        }
        isDesktopExist(e) {
            let t = Laya.Browser.window.qg;
            t.getSystemInfoSync().platformVersionCode < 1044 || (t.hasShortcutInstalled ? t.hasShortcutInstalled({
                success: function (t) {
                    e && e(t);
                },
                fail: function (e) { },
                complete: function () { }
            }) : e(!1));
        }
        putDesktop(e) {
            let t = Laya.Browser.window.qg;
            t.getSystemInfoSync().platformVersionCode < 1040 || t.hasShortcutInstalled({
                success: function (n) {
                    0 == n && t.installShortcut({
                        success: function () {
                            e && e();
                        },
                        fail: function (e) {
                            console.log("install", JSON.stringify(e));
                        },
                        complete: function () { }
                    });
                },
                fail: function (e) {
                    console.log("isshotcut", e);
                },
                complete: function () { }
            });
        }
        preloadNativeInterstitialAd(e, t = null) {
            e || (e = "6227e83836d248fd9ad3ab9ceb7ae548");
            let n, a, i = Laya.Browser.window.qg,
                s = this;
            n = i.createNativeAd({
                posId: e
            }), s.nativeAd = n, n.onLoad(function (e) {
                console.log("原生广告加载完成", JSON.stringify(e)), e && e.adList && (a = e.adList.pop(), console.log("nativeCurrentAdList", a), s.adId = a.adId, s.nativeCurrentAdList = a, null != t && t());
            }), n.onError(e => {
                switch (e.errCode) {
                    case -3:
                        console.error("原生广告加载失败---调用太频繁", JSON.stringify(e));
                        break;
                    default:
                        console.error("原生广告展示失败"), console.error(JSON.stringify(e));
                }
            }),
                function () {
                    let e = n.load();
                    e && e.then(() => { }).catch(e => {
                        console.error("原生加载失败", JSON.stringify(e));
                    });
                }();
        }
        showNativeInterstitialAdByPreload(e, t, n, a, i) {
            var s = this;

            function reportAdClick() {
                s.nativeAd.reportAdClick({
                    adId: s.adId.toString()
                });
            }
            if (console.log("查看广告按钮", t), i) {
                let i = "";
                e.loadImage(i, Laya.Handler.create(this, function () {
                    e.parent.visible = !0, e.on(Laya.Event.MOUSE_DOWN, this, function () {
                        console.log("点击原生");
                    }), t.on(Laya.Event.MOUSE_DOWN, this, function () {
                        a ? console.log("点击原生") : (console.log("点击跳过"), e.parent.visible = !1);
                    }), n.on(Laya.Event.MOUSE_DOWN, this, function () {
                        if (100 * Math.random() < s.setting.Lc_ADClickTouchType && s.xxNum > 0) {
                            s.xxNum--;
                            let e = Math.floor(Date.now() / 864e5);
                            Laya.LocalStorage.setJSON("XXnum", {
                                day: e,
                                index: s.xxNum
                            }), console.log("点击误触原生");
                        } else console.log("关闭原生");
                        e.parent.visible = !1;
                    });
                }));
            } else if (this.nativeCurrentAdList) {
                if (s.nativeAd.reportAdShow({
                    adId: s.adId.toString()
                }), e && t && (e.parent.visible = !1, s.nativeCurrentAdList.imgUrlList[0])) {
                    Laya.loader.load(s.nativeCurrentAdList.imgUrlList[0], Laya.Handler.create(this, function (i) {
                        i ? (console.log("res", typeof i), "string" == typeof i ? console.log("图片加载失败") : function () {
                            e.loadImage(s.nativeCurrentAdList.imgUrlList[0], Laya.Handler.create(this, function () {
                                console.log("加载图片完成"), e.parent.visible = !0, e.offAll(Laya.Event.MOUSE_DOWN), t.offAll(Laya.Event.MOUSE_DOWN), n.offAll(Laya.Event.MOUSE_DOWN), e.on(Laya.Event.MOUSE_DOWN, this, function () {
                                    e.parent.visible = !1, reportAdClick(), s.preloadNativeInterstitialAd("");
                                }), t.on(Laya.Event.MOUSE_DOWN, this, function () {
                                    a && reportAdClick(), e.parent.visible = !1, s.preloadNativeInterstitialAd("");
                                }), n.on(Laya.Event.MOUSE_DOWN, this, function () {
                                    if (100 * Math.random() < s.setting.Lc_ADClickTouchType && s.xxNum > 0) {
                                        reportAdClick(), s.xxNum--;
                                        let e = Math.floor(Date.now() / 864e5);
                                        Laya.LocalStorage.setJSON("XXnum", {
                                            day: e,
                                            index: s.xxNum
                                        });
                                    }
                                    e.parent.visible = !1, s.preloadNativeInterstitialAd("");
                                });
                            }));
                        }()) : console.log("图片加载失败");
                    }));
                }
            } else this.showNativeInterstitialAd(e, t, n, a, i);
        }
        showNativeInterstitialAd(e, t, n, a, i) {
            let s, o, r = Laya.Browser.window.qg,
                l = this;
            s = r.createNativeAd({
                posId: "6227e83836d248fd9ad3ab9ceb7ae548"
            }), l.nativeAd = s, s.onLoad(function (s) {
                if (console.log("原生广告加载完成", JSON.stringify(s)), s && s.adList) {
                    function reportAdClick() {
                        l.nativeAd.reportAdClick({
                            adId: l.adId.toString()
                        });
                    }
                    if (o = s.adList.pop(), console.log("nativeCurrentAdList", o), l.adId = o.adId, l.nativeCurrentAdList = o, i) {
                        let i = "";
                        return void e.loadImage(i, Laya.Handler.create(l, function () {
                            e.parent.visible = !0, e.on(Laya.Event.MOUSE_DOWN, l, function () {
                                console.log("点击原生");
                            }), t.on(Laya.Event.MOUSE_DOWN, l, function () {
                                a ? console.log("点击原生") : (console.log("点击跳过"), e.parent.visible = !1);
                            }), n.on(Laya.Event.MOUSE_DOWN, l, function () {
                                if (100 * Math.random() < l.setting.Lc_ADClickTouchType && l.xxNum > 0) {
                                    l.xxNum--;
                                    let e = Math.floor(Date.now() / 864e5);
                                    Laya.LocalStorage.setJSON("XXnum", {
                                        day: e,
                                        index: l.xxNum
                                    }), console.log("点击误触原生");
                                } else console.log("关闭原生");
                                e.parent.visible = !1;
                            });
                        }));
                    }
                    l.nativeCurrentAdList && (l.nativeAd.reportAdShow({
                        adId: l.adId.toString()
                    }), e && t && (e.parent.visible = !1, l.nativeCurrentAdList.imgUrlList[0])) && Laya.loader.load(l.nativeCurrentAdList.imgUrlList[0], Laya.Handler.create(l, function (i) {
                        i ? (console.log("res", typeof i), "string" == typeof i ? console.log("图片加载失败") : e.loadImage(l.nativeCurrentAdList.imgUrlList[0], Laya.Handler.create(l, function () {
                            console.log("加载图片完成"), e.parent.visible = !0, e.offAll(Laya.Event.MOUSE_DOWN), t.offAll(Laya.Event.MOUSE_DOWN), n.offAll(Laya.Event.MOUSE_DOWN), e.on(Laya.Event.MOUSE_DOWN, l, function () {
                                e.parent.visible = !1, reportAdClick();
                            }), t.on(Laya.Event.MOUSE_DOWN, l, function () {
                                a && reportAdClick(), e.parent.visible = !1;
                            }), n.on(Laya.Event.MOUSE_DOWN, l, function () {
                                if (100 * Math.random() < l.setting.Lc_ADClickTouchType && l.xxNum > 0) {
                                    reportAdClick(), l.xxNum--;
                                    let e = Math.floor(Date.now() / 864e5);
                                    Laya.LocalStorage.setJSON("XXnum", {
                                        day: e,
                                        index: l.xxNum
                                    });
                                }
                                e.parent.visible = !1;
                            });
                        }))) : console.log("图片加载失败");
                    }));
                }
            }), s.onError(e => {
                switch (e.errCode) {
                    case -3:
                        console.error("原生广告加载失败---调用太频繁", JSON.stringify(e));
                        break;
                    default:
                        console.error("原生广告展示失败"), console.error(JSON.stringify(e));
                }
            }),
                function () {
                    let e = s.load();
                    e && e.then(() => { }).catch(e => {
                        console.error("原生加载失败", JSON.stringify(e));
                    });
                }();
        }
        getSetting(e) {
            var t = this,
                n = "" + this.appid + "&channel=" + this.channel + "&AB_action=" + this.version;
            console.log("getSetting", n), u.get(n, this, function (n) {
                if (console.log(n), 200 == n.state) {
                    let a = n.data;
                    a && a.setting && (t.setting = a.setting, t.setting.Lc_AutoVideoGuide, console.log("设置开关", t.setting), console.log(JSON.stringify(t.setting)), e && e());
                }
            });
        }
    }
    g.instance = null;
    class y {
        static reportEvent(e, t = null) {
            let n, a, i, s, o, r, l;
            console.error("打点事件", e), Laya.Browser.onVVMiniGame ? (n = g.getInstance().openId, a = g.getInstance().packName, i = "vivo", o = g.getInstance().appid, r = g.getInstance().version, s = g.getInstance().channel, l = o + n) : Laya.Browser.onQGMiniGame ? l = o + n : Laya.Browser.onQQMiniGame || window.wx && (n = m.getInstance().getOpenId(), a = m.getInstance().getPkgName(), i = "wx", o = m.getInstance().getAppID(), r = m.getInstance().getVersion(), s = m.getInstance().getChannel(), l = o + n);
            var c = {};
            c.appid = o, c.uuid = n, c.pkgname = "", c.platform = i, c.version = r, c.c_ts = new Date().getTime(), c.event = e, c.data = JSON.stringify(t), c.channel = s, c.abtest = "A", c.appiduuid = o + n, c.data || (c.data = "");
            let h = JSON.stringify(c);
            console.log("uuid", n), n && n.length > 1 && ((c = JSON.parse(h)).appid = o, c.uuid = n, c.appiduuid = o + n, this.SendData(c, "lechangshanghai2052A"));
        }
        static SendData(e, t) {
            var n = u.sortObject(e),
                a = u.b64_hmac_sha1(t, u.objToUrl(n), !1, !1);
            let i = "" + u.objToUrl(n) + "&signature=" + a;
            console.log("reportEvent:", e.event, e), console.log("url:", i), u.get(i, this, function (t) {
                200 == t.state ? console.log("======request success======" + e.event) : console.log("======request fail======>" + e.event, t.msg);
            });
        }
    }
    class p {
        static reportEvent(t, n = null) {
            if (0 != e.Instance.GamePointReport)
                if (window.wx) {
                    if ("NewGame" == t.slice(0, 7)) {
                        if (0 == e.Instance.isNewUser) return;
                        if (-1 != this.reportEventStr.indexOf(t)) return;
                        this.reportEventStr.push(t);
                    }
                    console.log("上报事件", t), y.reportEvent(t, n);
                } else if (Laya.Browser.onVVMiniGame) {
                    if ("NewGame" == t.slice(0, 7)) {
                        if (0 == e.Instance.isNewUser) return;
                        if (-1 != this.reportEventStr.indexOf(t)) return;
                        this.reportEventStr.push(t);
                    }
                    console.log("上报事件", t), y.reportEvent(t, n);
                }
        }
        static AldStageOnStart(e) {
            Laya.Browser.onMiniGame && window.wx.aldStage.onStart(e);
        }
        static AldStageOnEnd(e) {
            Laya.Browser.onMiniGame && window.wx.aldStage.onEnd(e);
        }
        static showWXtishi() {
            Laya.Browser.onMiniGame && window.wx.showToast({
                title: "暂无广告",
                icon: "none",
                duration: 2e3
            });
        }
    }
    p.reportEventStr = [];
    class m {
        constructor() {
            this.shareTitle = "", this.shareImgUrl = "", this.bannerAd = [], this.openid = "", this.VERSION = "1.0.0", this.APPID = "wxbc525868a6242854", this.CHANNEL = "wx_kyx_PencilRush", this.PKGNAME = "com.lechang.pencilRush.wxminigame", this.VIDEO_ID = ["adunit-e89c4e59952f1685"], this.BANNER_ID = ["adunit-ae591d531ddd9c96"], this.showNum = [0, 0], this.setting = {
                Lc_GamePointReport: 0,
                Lc_GameOverType: 1,
                Lc_city: 1
            };
        }
        static getInstance() {
            return null == this.instance && (this.instance = new m()), this.instance;
        }
        init() {
            if (this.getSetting(null), !Laya.Browser.onMiniGame) return;
            let e = Laya.Browser.window.wx,
                t = this;
            this.sysInfo = e.getSystemInfoSync();
            this.sysInfo.screenWidth, this.sysInfo.screenHeight;
            e.updateShareMenu({
                withShareTicket: !0
            }), e.onShow(function () {
                console.log("回到前台"), h.getInstance().playerBGM();
            }), e.showShareMenu(), e.onShareAppMessage(function () {
                return {
                    title: t.shareTitle,
                    query: "key1=界面的三个点启动1",
                    imageUrl: t.shareImgUrl,
                    success: function () {
                        console.log("分享成功");
                    }
                };
            }), this.preloadAllBanner(), e.login({
                success(e) {
                    if (e.code) {
                        let n = "" + e.code + "&app_id=" + t.APPID;
                        u.get(n, this, function (e) {
                            200 == e.state ? (console.log("request success:", e.data), console.log(e.data), t.openid = e.data.openid, p.reportEvent("NewGame_Loading")) : console.log("request fail:", e.msg);
                        });
                    } else console.log("登录失败！" + e.errMsg);
                }
            });
        }
        share() {
            (Laya.Browser.onQQMiniGame ? Laya.Browser.window.wx : wx).shareAppMessage({
                title: this.shareTitle,
                imageUrl: this.shareImgUrl,
                query: ""
            });
        }
        showVideo(e, t, n) {
            let a = Laya.Browser.window.wx;
            a.showLoading({
                title: "加载中"
            });
            let i = this,
                s = this.VIDEO_ID[e];
            null == this.videoAd ? this.videoAd = a.createRewardedVideoAd({
                adUnitId: s
            }) : this.videoAd.load(), h.getInstance().stopBGM(), this.videoAd.show().then(() => {
                wx.hideLoading(), console.log("激励视频 广告显示");
            }).catch(() => {
                wx.hideLoading(), i.videoAd.load().then(() => i.videoAd.show()).catch(e => {
                    console.log("激励视频 广告显示失败");
                });
            }), this.videoAd.onClose(function (e) {
                console.log("videoAd onClose", e), e && e.isEnded ? t && (h.getInstance().recoverBGM(), t()) : n && (h.getInstance().recoverBGM(), n()), i.videoAd.offClose(), wx.hideLoading();
            }), this.videoAd.onError(e => {
                wx.hideLoading(), console.log(e), n && n(), i.videoAd.offError();
            });
        }
        getOpenId() {
            return this.openid;
        }
        getPkgName() {
            return this.PKGNAME;
        }
        getAppID() {
            return this.APPID;
        }
        getVersion() {
            return this.VERSION;
        }
        getChannel() {
            return this.CHANNEL;
        }
        preloadAllBanner() { }
        preloadBanner(e) { }
        showBannerNotCreat(e = 0) { }
        hideBanner() { }
        showAppBox() { }
        getSetting(t) {
            var n = this,
                a = "" + this.CHANNEL + "&AB_action=1";
            console.log("getSetting", a), u.get(a, this, function (a) {
                if (console.log(a), 200 == a.state) {
                    let i = a.data;
                    i && i.setting && (n.setting = i.setting, console.log("设置开关", n.setting), console.log(JSON.stringify(n.setting)), 1 == n.setting.Lc_GamePointReport ? e.Instance.GamePointReport = !0 : e.Instance.GamePointReport = !1, t && t());
                }
            });
        }
    }
    m.instance = null;
    class L {
        constructor() {
            this.isPlaying = !1, this.isplay = !1;
        }
        static getInstance() {
            return null == this.instance && (this.instance = new L()), this.instance;
        }
        playSound(e) {
            Laya.loader.load("res/pkg/Sounds/" + e + ".mp3", Laya.Handler.create(this, () => {
                this.sound = Laya.SoundManager.playSound("res/pkg/Sounds/" + e + ".mp3");
            }))
        }
        playerBGM() {
            Laya.loader.load("res/pkg/Sounds/bgm.mp3", Laya.Handler.create(this, () => {
                this.s = Laya.SoundManager.playMusic("res/pkg/Sounds/bgm.mp3", 0);
            }))
        }
        recoverBGM() {
            this.s && this.s.resume();
        }
        stopBGM() {
            this.s && this.s.pause();
        }
        init() { }
        playerFoot() {
            let e = this;
            this.isplay || (this.isplay = !0, this.jiaobu = Laya.SoundManager.playSound("res/pkg/Sounds/footstep.mp3"), this.jiaobu.completeHandler = Laya.Handler.create(this, function () {
                e.isplay = !1;
            }));
        }
    }
    L.instance = null;
    class f extends Laya.Script3D {
        constructor() {
            super(...arguments), this.scaleYspeed = .2, this.isCanScale = !1, this.returnSpeed = 70, this.lrcucaodu = 3, this.lrRotateSpeed = 1, this.t = 0;
        }
        onAwake() {
            this.gameObject = this.owner, this.parent = this.gameObject.parent, this.rig = this.gameObject.getComponent(Laya.Rigidbody3D), this.rig.isKinematic = !0, this.playerSc = this.gameObject.parent.parent.getComponent(I), this.trail = this.parent.getChildAt(1), this.trail.trailRenderer.enable = !0, this.gameObject.layer = 0, this.initTrail(), this.particle = Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(0), this.owner, !1), this.particle.transform.localPosition = new Laya.Vector3(0, 0, 0), this.particle.particleRenderer.material.color = this.gameObject.meshRenderer.materials[0].albedoColor, this.particle.particleSystem.play(), this.returnSpeed = e.Instance.pencilRotateSpeed, this.lrcucaodu = e.Instance.lrcucaodu, this.lrRotateSpeed = e.Instance.lrRotateSpeed, this.gameObject.transform.setWorldLossyScale(new Laya.Vector3(1.07, 1.07, 1.07)), this.gameObject.once("remove", this, this.onRemoveMySelf);
        }
        onUpdate() {
            if (this.playerSc.isFinish || this.playerSc.isOver || 0 == this.playerSc.startGame) this.gameObject.transform.rotationEuler = new Laya.Vector3(0, 0, 0);
            else if (this.scaleYspeed = e.Instance.intensify_PencilLoss[e.Instance.intensify.pencilLossIntensify - 1][2], o.getInstance().dataMouseX1 < this.lrcucaodu && o.getInstance().dataMouseX1 > -this.lrcucaodu && (o.getInstance().dataMouseX1 = 0), this.t += o.getInstance().dataMouseX1 * this.lrRotateSpeed, this.t > 5 ? this.t -= .001 * Laya.timer.delta * this.returnSpeed : this.t < -5 ? this.t += .001 * Laya.timer.delta * this.returnSpeed : this.t = 0, this.t > 20 ? this.t = 20 : this.t < -20 && (this.t = -20), this.gameObject.transform.rotationEuler = new Laya.Vector3(0, 0, -this.t), this.isCanScale) {
                let e = this.gameObject.transform.localScale;
                if (!(e.y > .1)) return void this.gameObject.event("remove");
                e.y -= 1e-4 * Laya.timer.delta * this.scaleYspeed, this.gameObject.transform.localScale = e;
            }
        }
        onLateUpdate() {
            o.getInstance().dataMouseX1 = 0;
        }
        onTriggerEnter(e) {
            let t = e.owner;
            switch (t.layer) {
                case 9:
                    this.onTriggerSpecil(t), this.playerSc.addPencil(t.parent), t.layer = 0;
                    break;
                case 10:
                    0 == this.playerSc.isFinish && (this.playerSc.isFinish = !0, P.instance.handBox.visible = !0, p.reportEvent("NewGame_FinishLineDrawHitShow"), p.reportEvent("NewGame_FinishLine"), m.getInstance().hideBanner()), this.gameObject.transform.rotationEuler = new Laya.Vector3(0, 0, 0), this.playerSc.owner.transform.position = new Laya.Vector3(0, 0, this.playerSc.owner.transform.position.z), this.hideTrail();
                    break;
                case 11:
                    if (this.rig.isKinematic) {
                        console.log("障碍物"), this.rig.isKinematic = !1, this.rig.gravity = new Laya.Vector3(0, -9.8, 0);
                        let e = this.parent.transform.position;
                        this.parent.removeSelf(), this.rig.applyForce(new Laya.Vector3(0, 0, -30)), s.Instance.currentLevelSp.addChild(this.parent), this.rig.isTrigger = !1, this.parent.transform.position = e;
                        let t = this;
                        t.playerSc.updatePencilPos(2e3), t.destroy(), L.getInstance().playSound("trigger");
                    }
                    break;
                case 12:
                    t.layer = 0;
                    let e = t.parent.parent.parent.getChildAt(0),
                        n = e.getChildAt(0).transform.position,
                        a = function () {
                            let t = e.getChildAt(1);
                            for (let e = 0; e < t.numChildren; e++) {
                                let a = t.getChildAt(e),
                                    s = a.getComponent(Laya.Rigidbody3D);
                                s.isKinematic = !1, s.gravity = new Laya.Vector3(0, -9.8, 0), s.applyForce(i.Vector3.multiply(n, i.MathTool.getRandomNum(1, 5))), Laya.timer.once(1e3, null, function () {
                                    a.destroy();
                                });
                            }
                            Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(2), e).transform.localPosition = new Laya.Vector3(0, 0, 0);
                        };
                    this.playerSc.flyToGlass(n, Laya.Handler.create(this, a)), p.reportEvent("NewGame_AttGlass");
                    break;
                case 13:
                    if (this.rig.isKinematic && 0 == this.playerSc.isFinish) {
                        console.log("墙", t.name), this.rig.isKinematic = !1, this.rig.gravity = new Laya.Vector3(0, -9.8, 0);
                        let e = this.parent.transform.position;
                        this.parent.removeSelf(), this.rig.applyForce(new Laya.Vector3(30 * e.x, 0, 0)), s.Instance.currentLevelSp.addChild(this.parent), this.rig.isTrigger = !1, this.parent.transform.position = e;
                        let n = this;
                        n.playerSc.updatePencilPos(2e3), n.destroy();
                    }
            }
        }
        onTriggerSpecil(e) {
            switch (e.parent.name) {
                case "0": {
                    e.layer = 0;
                    let t = e.getChildAt(0);
                    t.transform.localPosition = new Laya.Vector3(0, 0, 0), t.getComponent(Laya.Animator).enabled = !1, N.Instance.changeSpecialPencil(N.Instance.colorSpList[0], 0), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(4), s.Instance.currentLevelSp).transform.position = new Laya.Vector3(e.transform.position.x, e.transform.position.y + .5, e.transform.position.z);
                }
                    break;
                case "1": {
                    e.layer = 0;
                    let t = e.getChildAt(0);
                    t.transform.localPosition = new Laya.Vector3(0, 0, 0), t.getComponent(Laya.Animator).enabled = !1, N.Instance.changeSpecialPencil(N.Instance.colorSpList[1], 1), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(4), s.Instance.currentLevelSp).transform.position = new Laya.Vector3(e.transform.position.x, e.transform.position.y + .5, e.transform.position.z);
                }
                    break;
                case "2": {
                    e.layer = 0;
                    let t = e.getChildAt(0);
                    t.transform.localPosition = new Laya.Vector3(0, 0, 0), t.getComponent(Laya.Animator).enabled = !1, N.Instance.changeSpecialPencil(N.Instance.colorSpList[2], 2), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(4), s.Instance.currentLevelSp).transform.position = new Laya.Vector3(e.transform.position.x, e.transform.position.y + .5, e.transform.position.z);
                }
                    break;
                case "3": {
                    e.layer = 0;
                    let t = e.getChildAt(0);
                    t.transform.localPosition = new Laya.Vector3(0, 0, 0), t.getComponent(Laya.Animator).enabled = !1, N.Instance.changeSpecialPencil(N.Instance.colorSpList[3], 3), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(4), s.Instance.currentLevelSp).transform.position = new Laya.Vector3(e.transform.position.x, e.transform.position.y + .5, e.transform.position.z);
                }
                    break;
                case "4": {
                    e.layer = 0;
                    let t = e.getChildAt(0);
                    t.transform.localPosition = new Laya.Vector3(0, 0, 0), t.getComponent(Laya.Animator).enabled = !1, N.Instance.changeSpecialPencil(N.Instance.colorSpList[4], 4), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(4), s.Instance.currentLevelSp).transform.position = new Laya.Vector3(e.transform.position.x, e.transform.position.y + .5, e.transform.position.z);
                }
                    break;
                case "5": {
                    e.layer = 0;
                    let t = e.getChildAt(0);
                    t.transform.localPosition = new Laya.Vector3(0, 0, 0), t.getComponent(Laya.Animator).enabled = !1, N.Instance.changeSpecialPencil(N.Instance.colorSpList[5], 5), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(4), s.Instance.currentLevelSp).transform.position = new Laya.Vector3(e.transform.position.x, e.transform.position.y + .5, e.transform.position.z);
                }
                    break;
                case "6": {
                    e.layer = 0;
                    let t = e.getChildAt(0);
                    t.transform.localPosition = new Laya.Vector3(0, 0, 0), t.getComponent(Laya.Animator).enabled = !1, N.Instance.changeSpecialPencil(N.Instance.colorSpList[6], 6), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(4), s.Instance.currentLevelSp).transform.position = new Laya.Vector3(e.transform.position.x, e.transform.position.y + .5, e.transform.position.z);
                }
            }
        }
        onRemoveMySelf() {
            this.parent.removeSelf(), this.parent.destroy();
            this.playerSc.updatePencilPos(), this.destroy();
        }
        initTrail() {
            let e = this.trail.trailRenderer.material,
                t = this.gameObject.meshRenderer.materials[0].albedoColor,
                n = new Laya.Vector4();
            n.setValue(.9 * t.x, .9 * t.y, .9 * t.z, 1), e.color = n;
        }
        hideTrail() {
            this.trail.active = !1, this.particle.active = !1, this.isCanScale = !1;
        }
        showTrail() {
            this.trail.active = !0, this.particle.active = !0, this.isCanScale = !0;
        }
        onDestroy() {
            this.hideTrail();
        }
    }
    class I extends i.Script3D {
        constructor() {
            super(...arguments), this._startGame = !1, this.moveSpeed = 2.5, this.LRSpeed = .5, this.isFinish = !1, this.isOver = !1, this._CameraHeight = 1.8, this._CameraDistance = 3, this.maxMouseX = 3, this.smothing = 5, this.lookY = 0, this.isStopFollow = !1, this._updatePencilPosing = !1, this.isHaveOpenBox = !1;
        }
        set startGame(e) {
            this._startGame = e;
        }
        get startGame() {
            return this._startGame;
        }
        onAwake() {
            super.onAwake(), this.init();
        }
        init() {
            this.moveSpeed = e.Instance.pencilMoveSpeed, this.LRSpeed = e.Instance.pencilLRSpeed, this.smothing = e.Instance.cameraSmoth;
            let t = e.Instance.intensify_PencilNum[e.Instance.intensify.pencilNum - 1][2];
            for (let n = 0; n < e.Instance.pencilNum + t; n++) {
                let e = this.gameObject.addChild(s.Instance.pre_pencil.clone()),
                    t = i.MathTool.getRandomInt(N.Instance.colorList.length),
                    n = N.Instance.colorList[t].clone(),
                    a = N.Instance.colorList2[t].clone();
                e.getChildAt(0).meshRenderer.materials[0].albedoColor = n, e.getChildAt(0).meshRenderer.materials[1].albedoColor = a, e.getChildAt(0).addComponent(f).hideTrail();
            }
            this.updatePencilPos(), this.initCamera(), this.initEvent();
        }
        addPencilQianghua() {
            let e = this.gameObject.addChild(s.Instance.pre_pencil.clone()),
                t = i.MathTool.getRandomInt(N.Instance.colorList.length),
                n = N.Instance.colorList[t].clone(),
                a = N.Instance.colorList2[t].clone();
            e.getChildAt(0).meshRenderer.materials[0].albedoColor = n, e.getChildAt(0).meshRenderer.materials[1].albedoColor = a, e.getChildAt(0).addComponent(f).hideTrail(), this.updatePencilPos();
        }
        onOpenPencilBox() {
            for (let t = 0; t < e.Instance.moheNum; t++) {
                let e = this.gameObject.addChild(s.Instance.pre_pencil.clone()),
                    t = i.MathTool.getRandomInt(N.Instance.colorList.length),
                    n = N.Instance.colorList[t].clone(),
                    a = N.Instance.colorList2[t].clone();
                e.getChildAt(0).meshRenderer.materials[0].albedoColor = n, e.getChildAt(0).meshRenderer.materials[1].albedoColor = a, e.getChildAt(0).addComponent(f).hideTrail();
            }
            this.updatePencilPos();
        }
        initEvent() {
            this.gameObject.once("Fail", this, this.onFail), this.gameObject.once("OpenBox", this, this.onOpenBox), this.gameObject.once("win", this, this.onWin);
        }
        initCamera() {
            s.Instance.Camera.transform.position = new Laya.Vector3(this.transform.position.x, this.transform.position.y + this._CameraHeight, this.transform.position.z - this._CameraDistance);
            let e = new Laya.Vector3(this.transform.position.x, this.transform.position.y, this.transform.position.z);
            s.Instance.Camera.transform.lookAt(e, new Laya.Vector3(0, 1, 0));
        }
        onUpdate() {
            if (0 == this._startGame || this.isFinish || this.isOver) return;
            let e = this.transform.position;
            e.x -= o.getInstance().dataMouseX * this.LRSpeed, e.z += Laya.timer.delta * this.moveSpeed * .001, this.transform.position = e;
        }
        onLateUpdate() {
            if (0 == this._startGame || this.isStopFollow) return;
            if (this.isFinish) {
                let e = s.Instance.currentPicture.parent.transform.position;
                this._CameraHeight = e.y - 1, this._CameraDistance = 5, this.lookY < this._CameraHeight && (this.lookY += .001 * Laya.timer.delta * 2), s.Instance.Camera.transform.lookAt(new Laya.Vector3(0, this.lookY, e.z), new Laya.Vector3(0, 1, 0));
            }
            let e = new Laya.Vector3(this.transform.position.x, this.transform.position.y + this._CameraHeight, this.transform.position.z - this._CameraDistance),
                t = new Laya.Vector3();
            Laya.Vector3.lerp(s.Instance.Camera.transform.position, e, this.smothing * Laya.timer.delta * .001, t), s.Instance.Camera.transform.position = t;
            let n = new Laya.Vector3(t.x, this.transform.position.y, this.transform.position.z);
            0 == this.isFinish && s.Instance.Camera.transform.lookAt(n, new Laya.Vector3(0, 1, 0)), o.getInstance().dataMouseX = 0;
        }
        addPencil(e) {
            i.Platform.vibration(), L.getInstance().playSound("add1");
            let t = this,
                n = new Laya.Vector3(0, 0, 0);
            n = e.transform.position.clone(), e.removeSelf();
            let a = this.gameObject.addChild(e);
            a.getChildAt(1).trailRenderer.enable = !1, a.transform.position = n;
            let s = new Laya.Vector3(0, 0, 0);
            this.gameObject.numChildren % 2 != 0 ? s.setValue(this.transform.position.x + this.gameObject.numChildren % 10 * .07, 0, this.transform.position.z + .14 * Math.floor(this.gameObject.numChildren / 20)) : s.setValue(this.transform.position.x - this.gameObject.numChildren % 10 * .07, 0, this.transform.position.z + .14 * Math.floor(this.gameObject.numChildren / 20));
            let o = i.Vector3.subtract(s, this.transform.position),
                r = {
                    rotationX: e.transform.rotationEuler.x,
                    rotationY: e.transform.rotationEuler.y,
                    rotationZ: e.transform.rotationEuler.z,
                    postionX: e.transform.localPosition.x,
                    postionY: e.transform.localPosition.y,
                    postionZ: e.transform.localPosition.z
                },
                l = {
                    rotationX: 0,
                    rotationY: 0,
                    rotationZ: 0,
                    postionX: o.x,
                    postionY: o.y,
                    postionZ: o.z,
                    update: new Laya.Handler(t, function () {
                        t.gameObject.destroyed || (a.transform.rotationEuler = new Laya.Vector3(r.rotationX, r.rotationY, r.rotationZ), a.transform.localPosition = new Laya.Vector3(r.postionX, r.postionY, r.postionZ));
                    })
                };
            Laya.Tween.to(r, l, 300, Laya.Ease.linearIn, Laya.Handler.create(this, function () {
                if (t.gameObject.destroyed) return;
                a.getChildAt(0).addComponent(f).hideTrail(), t.updatePencilPos();
            }));
        }
        flyPencil() {
            if (this.gameObject.numChildren <= 0) return void (this.isFinish && (p.reportEvent("NewGame_FinishLineDrawOver"), p.reportEvent("NewGame_MoBoxShow"), this.gameObject.event("OpenBox")));
            p.reportEvent("NewGame_FinishLineDraw");
            let t = this,
                n = this.gameObject.getChildAt(this.gameObject.numChildren - 1),
                a = n.transform.position.clone();
            n.removeSelf();
            let o = s.Instance.currentLevelSp.addChild(n);
            o.transform.position = a;
            let r = o.getChildAt(0).getComponent(f);
            r && (r.hideTrail(), r.enabled = !1, r.destroy(), r = null, console.log("销毁组件"));
            let l = N.Instance.getPos();
            this.playPencilAni(o, l, Laya.Handler.create(this, function () {
                let n = new Laya.Vector3(o.transform.position.x, o.transform.position.y, o.transform.position.z - 1),
                    a = Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(1), s.Instance.currentLevelSp, !1, n);
                if (a.getChildAt(0).particleRenderer.material.color = o.getChildAt(0).meshRenderer.materials[1].albedoColor, a.getChildAt(1).particleRenderer.material.color = o.getChildAt(0).meshRenderer.materials[1].albedoColor, L.getInstance().playSound("hit_coin"), i.Platform.vibration(), o.destroy(!0), e.Instance.PictureData.currentPictureProgress < 25)
                    for (let t = 0; t < e.Instance.picturePoint; t++) N.Instance.Update();
                else N.Instance.Update();
                t.gameObject.numChildren <= 0 && t.isFinish && (0 == t.isHaveOpenBox ? t.gameObject.event("OpenBox") : t.gameObject.event("win"));
            }));
        }
        flyToGlass(e, t) {
            if (this.gameObject.numChildren <= 0) return void this.gameObject.event("Fail");
            let n = this,
                a = this.gameObject.getChildAt(this.gameObject.numChildren - 1),
                i = a.transform.position.clone();
            a.removeSelf();
            let o = s.Instance.currentLevelSp.addChild(a);
            o.transform.position = i;
            let r = o.getChildAt(0).getComponent(f);
            r && (r.showTrail(), r.destroy()), this.playPencilAni(o, e, Laya.Handler.create(this, function () {
                t.run(), o.destroy(!0), n.updatePencilPos(), L.getInstance().playSound("glass");
            }));
        }
        updatePencilPos(e = null) {
            if (this._updatePencilPosing) return;
            let t = this,
                n = t.gameObject.numChildren;
            if (n <= 0) return t.isOver = !0, void t.gameObject.event("Fail");
            this.reportEvent(n);
            let a = function () {
                let e = 0,
                    n = 1,
                    a = t.gameObject.numChildren;
                if (a <= 0) return t.isOver = !0, void t.gameObject.event("Fail");
                for (let i = 0; i < a; i++) {
                    if (i < 20) {
                        let e = t.gameObject.getChildAt(i).getChildAt(0).getComponent(f);
                        e && e.showTrail();
                    }
                    let a = .14 * Math.floor(i / 20);
                    if (i % 2 == 0) {
                        let n = .07 * e;
                        n -= .7 * Math.floor(i / 20), t.moveTo3d(t.gameObject.getChildAt(i), new Laya.Vector3(n, 0, a), 200, !0, t.gameObject, Laya.Handler.create(this, function () {
                            t._updatePencilPosing = !1;
                        })), e++;
                    } else {
                        let e = -.07 * n;
                        e += .7 * Math.floor(i / 20), t.moveTo3d(t.gameObject.getChildAt(i), new Laya.Vector3(e, 0, a), 200, !0, t.gameObject, Laya.Handler.create(this, function () {
                            t._updatePencilPosing = !1;
                        })), n++;
                    }
                }
            };
            e ? Laya.timer.once(e, this, function () {
                a();
            }) : a();
        }
        reportEvent(e) {
            10 == e ? p.reportEvent("NewGame_PenNum10") : 15 == e ? p.reportEvent("NewGame_PenNum15") : 20 == e ? p.reportEvent("NewGame_PenNum20") : 30 == e ? p.reportEvent("NewGame_PenNum30") : 35 == e ? p.reportEvent("NewGame_PenNum35") : 40 == e ? p.reportEvent("NewGame_PenNum40") : 45 == e ? p.reportEvent("NewGame_PenNum45") : 50 == e ? p.reportEvent("NewGame_PenNum50") : 55 == e ? p.reportEvent("NewGame_PenNum55") : 60 == e ? p.reportEvent("NewGame_PenNum60") : 65 == e && p.reportEvent("NewGame_PenNum65");
        }
        moveTo3d(e, t, n, a = !1, i, s = null) {
            let o = new Laya.Vector3(),
                r = {
                    x: (o = a ? e.transform.localPosition.clone() : e.transform.position.clone()).x,
                    y: o.y,
                    z: o.z
                },
                l = {
                    x: t.x,
                    y: t.y,
                    z: t.z,
                    update: new Laya.Handler(this, function () {
                        e.destroyed || e.parent != i ? c.clear() : a ? e.transform.localPosition = new Laya.Vector3(r.x, r.y, r.z) : e.transform.position = new Laya.Vector3(r.x, r.y, r.z);
                    })
                },
                c = Laya.Tween.to(r, l, n, Laya.Ease.linearIn, Laya.Handler.create(this, function () {
                    c.clear(), s && s.run();
                }));
        }
        playPencilAni(e, t, n = null) {
            let a = e.transform.position.clone(),
                i = e.transform.rotationEuler.clone(),
                s = this;
            e.transform.lookAt(t, new Laya.Vector3(0, 1, 0));
            let o = e.transform.rotationEuler.clone(),
                r = new Laya.Vector3(o.x + 90, o.y, o.z);
            e.transform.rotationEuler = new Laya.Vector3(0, 0, 0);
            let l = {
                x: a.x,
                y: a.y,
                z: a.z,
                rx: i.x,
                ry: i.y,
                rz: i.z
            },
                c = {
                    x: a.x,
                    y: a.y + 1,
                    z: a.z,
                    rx: r.x,
                    ry: r.y,
                    rz: r.z,
                    update: new Laya.Handler(this, function () {
                        s.destroyed || (e.transform.position = new Laya.Vector3(l.x, l.y, l.z), e.transform.rotationEuler = new Laya.Vector3(l.rx, l.ry, l.rz));
                    })
                },
                h = t.clone();
            this.transform.position.z;
            Laya.Tween.to(l, c, 500, Laya.Ease.quadIn, Laya.Handler.create(this, function () {
                if (s.destroyed) return;
                let a = e.transform.position.clone(),
                    i = {
                        x: a.x,
                        y: a.y,
                        z: a.z
                    },
                    o = {
                        x: t.x,
                        y: t.y,
                        z: t.z,
                        update: new Laya.Handler(this, function () {
                            if (s.destroyed) return;
                            e.transform.position = new Laya.Vector3(i.x, i.y, i.z);
                            let t = new Laya.Vector3(h.x, h.y, h.z);
                            e.transform.lookAt(t, new Laya.Vector3(0, 1, 0)), e.transform.rotationEuler = new Laya.Vector3(e.transform.rotationEuler.x + 90, e.transform.rotationEuler.y, e.transform.rotationEuler.z);
                        })
                    };
                Laya.Tween.to(i, o, 400, Laya.Ease.linearIn, Laya.Handler.create(this, function () {
                    s.destroyed || n && n.run();
                }));
            }));
        }
        onFail() {
            Laya.Scene.open(c.FailScene);
        }
        onOpenBox() {
            this.isStopFollow = !0, Laya.Scene.open(c.OpenPencilBoxScene, !1), P.instance && (P.instance.visible = !1);
        }
        onWin() {
            Laya.Scene.open(c.WinScene);
        }
        onDestroy() { }
    }
    var S, v, w, x = Laya.Scene,
        C = Laya.ClassUtils.regClass;
    ! function (e) {
        ! function (e) {
            class t extends x {
                constructor() {
                    super();
                }
                createChildren() {
                    super.createChildren(), this.loadScene("Views/FailScene");
                }
            }
            e.FailSceneUI = t, C("ui.Views.FailSceneUI", t);
            class n extends x {
                constructor() {
                    super();
                }
                createChildren() {
                    super.createChildren(), this.loadScene("Views/GameScene");
                }
            }
            e.GameSceneUI = n, C("ui.Views.GameSceneUI", n);
            class a extends x {
                constructor() {
                    super();
                }
                createChildren() {
                    super.createChildren(), this.loadScene("Views/LobbyScene");
                }
            }
            e.LobbySceneUI = a, C("ui.Views.LobbySceneUI", a);
            class i extends x {
                constructor() {
                    super();
                }
                createChildren() {
                    super.createChildren(), this.loadScene("Views/OpenPencilBoxScene");
                }
            }
            e.OpenPencilBoxSceneUI = i, C("ui.Views.OpenPencilBoxSceneUI", i);
            class s extends x {
                constructor() {
                    super();
                }
                createChildren() {
                    super.createChildren(), this.loadScene("Views/PictureScene");
                }
            }
            e.PictureSceneUI = s, C("ui.Views.PictureSceneUI", s);
            class o extends x {
                constructor() {
                    super();
                }
                createChildren() {
                    super.createChildren(), this.loadScene("Views/SkinScene");
                }
            }
            e.SkinSceneUI = o, C("ui.Views.SkinSceneUI", o);
            class r extends x {
                constructor() {
                    super();
                }
                createChildren() {
                    super.createChildren(), this.loadScene("Views/SpecialSkinScene");
                }
            }
            e.SpecialSkinSceneUI = r, C("ui.Views.SpecialSkinSceneUI", r);
            class l extends x {
                constructor() {
                    super();
                }
                createChildren() {
                    super.createChildren(), this.loadScene("Views/WinScene");
                }
            }
            e.WinSceneUI = l, C("ui.Views.WinSceneUI", l);
        }(e.Views || (e.Views = {}));
    }(S || (S = {}));
    class _ extends Laya.Script {
        onStart() { }
        creatAddOne(e) {
            let t = Laya.Pool.getItemByCreateFun("addOne", this.addOne.create, this.addOne);
            return t.pos(e.x, e.y), this.owner.addChildAt(t, 0), t;
        }
    } ! function (e) {
        e[e.coinNum = 0] = "coinNum", e[e.level = 1] = "level", e[e.intensify = 2] = "intensify", e[e.newUser = 3] = "newUser", e[e.pictureData = 4] = "pictureData", e[e.album = 5] = "album";
    }(v || (v = {}));
    class A {
        static saveData(t, n) {
            if (0 != e.Instance.isLoad) switch (t) {
                case v.coinNum:
                    Laya.LocalStorage.setItem(this.gameName + "coinNum", n);
                    break;
                case v.level:
                    Laya.LocalStorage.setItem(this.gameName + "level", n);
                    break;
                case v.intensify:
                    Laya.LocalStorage.setJSON(this.gameName + "intensify", n);
                    break;
                case v.newUser:
                    Laya.LocalStorage.setItem(this.gameName + "newUser", n);
                    break;
                case v.pictureData:
                    Laya.LocalStorage.setJSON(this.gameName + "pictureData", n);
                    break;
                case v.album:
                    Laya.LocalStorage.setJSON(this.gameName + "album", n);
            }
        }
        static loadData() {
            0 != e.Instance.isLoad && (Laya.LocalStorage.getItem(this.gameName + "coinNum") && (e.Instance.coinNum = parseInt(Laya.LocalStorage.getItem(this.gameName + "coinNum"))), Laya.LocalStorage.getItem(this.gameName + "level") && (e.Instance.currentLevel = parseInt(Laya.LocalStorage.getItem(this.gameName + "level"))), Laya.LocalStorage.getJSON(this.gameName + "intensify") && (e.Instance.intensify = Laya.LocalStorage.getJSON(this.gameName + "intensify")), Laya.LocalStorage.getItem(this.gameName + "newUser") && (e.Instance.isNewUser = !1), Laya.LocalStorage.getJSON(this.gameName + "pictureData") && (e.Instance.PictureData = Laya.LocalStorage.getJSON(this.gameName + "pictureData")), Laya.LocalStorage.getJSON(this.gameName + "album") && (e.Instance.album = Laya.LocalStorage.getJSON(this.gameName + "album")));
        }
    }
    A.gameName = "Pencil-Rush-Online-",
        function (e) {
            class t {
                constructor() { }
                static getInstance() {
                    return null == t.instance && (t.instance = new t()), t.instance;
                }
                isNull(e) {
                    return null == e || 0 === e.length || "undefined" === e || "null" === e || NaN === e;
                }
            }
            let n, a;
            t.instance = null, e.LanguageToolIns = t.getInstance(),
                function (e) {
                    e[e.SAMEDIRECTION = 0] = "SAMEDIRECTION", e[e.VERTICAL = 1] = "VERTICAL", e[e.OPPOSITEDIRECTION = 2] = "OPPOSITEDIRECTION";
                }(n = e.RelationForPointPlane || (e.RelationForPointPlane = {}));
            class i {
                constructor(e, t, n, a) {
                    this.triangle = e, this.point = t, this.otherPoint = n, this.index = a;
                }
            }
            class s {
                constructor(e, t) {
                    this.center = e, this.radio = t;
                }
            } ! function (e) {
                e[e.X = 0] = "X", e[e.Y = 1] = "Y", e[e.Z = 2] = "Z";
            }(a || (a = {}));
            class o {
                constructor(e, t, n) {
                    this.ABC = e, this.usexyz = t, this.points = n;
                }
            }
            class r {
                constructor() { }
                static getInstance() {
                    return null == r.instance && (r.instance = new r()), r.instance;
                }
                ComputeBezier(e, t, n) {
                    let a, i;
                    for (a = 1 / (t - 1), i = 0; i < t; i++) n[i] = this.PointOnCubicBezier(e, i * a);
                }
                PointOnCubicBezier(e, t) {
                    let n, a, i, s, o, r, l, c, h = new Laya.Vector2();
                    return i = 3 * (e[1].x - e[0].x), a = 3 * (e[2].x - e[1].x) - i, n = e[3].x - e[0].x - i - a, r = 3 * (e[1].y - e[0].y), o = 3 * (e[2].y - e[1].y) - r, s = e[3].y - e[0].y - r - o, c = (l = t * t) * t, h.x = n * c + a * l + i * t + e[0].x, h.y = s * c + o * l + r * t + e[0].y, h;
                }
                pointRotateByOtherPoint(e, t, n) {
                    n *= 3.14 / 180;
                    let a = new Laya.Vector2();
                    return a.x = (t.x - e.x) * Math.cos(n) - (t.y - e.y) * Math.sin(n) + e.x, a.y = (t.x - e.x) * Math.sin(n) + (t.y - e.y) * Math.cos(n) + e.y, a;
                }
                getNormalVectorByPlane(e) {
                    let t = e[0],
                        n = e[1],
                        a = e[2],
                        i = new Laya.Vector3(n.x - t.x, n.y - t.y, n.z - t.z),
                        s = new Laya.Vector3(a.x - t.x, a.y - t.y, a.z - t.z),
                        o = i.x,
                        r = i.y,
                        l = i.z,
                        c = s.x,
                        h = s.y,
                        d = s.z;
                    return new Laya.Vector3(r * d - h * l, l * c - d * o, o * h - c * r);
                }
                isCollinearByThreeVec3(e, t, n) {
                    var a = this.getDistanceByTwoPoint(e, t),
                        i = this.getDistanceByTwoPoint(t, n),
                        s = this.getDistanceByTwoPoint(e, n),
                        o = .5 * (a + i + s);
                    return !(o * (o - a) * (o - i) * (o - s));
                }
                getPlanePoints(e) {
                    for (var t = 0; t < e.length; t++)
                        for (var n = 0; n < e.length; n++)
                            if (n != t)
                                for (var a = 0; a < e.length; a++)
                                    if (a != n) {
                                        if (!this.isCollinearByThreeVec3(e[t], e[n], e[a])) return [e[t], e[n], e[a]];
                                    }
                    return null;
                }
                getNormalVectorByPoint(e) {
                    let t = new Laya.Vector3(0, 0, 0);
                    for (var n in e) {
                        let a = this.getNormalVectorByPlane(e[n]);
                        t.x += a.x, t.y += a.y, t.z += a.z;
                    }
                    return t;
                }
                getRelationForPointWithPlane(e, t, a) {
                    let i = new Laya.Vector3(t.x - e.x, t.y - e.y, t.z - e.z),
                        s = a,
                        o = (i.x * s.x + i.y * s.y + i.z * s.z) / (Math.sqrt(i.x * i.x + i.y * i.y + i.z * i.z) * Math.sqrt(s.x * s.x + s.y * s.y + s.z * s.z));
                    return o > 0 ? n.SAMEDIRECTION : 0 == o ? n.VERTICAL : n.OPPOSITEDIRECTION;
                }
                getCoefficientByPlanes(e) {
                    let t = e[0],
                        n = e[1],
                        a = e[2],
                        i = this.getNormalVectorByPlane([t, n, a]),
                        s = i.x,
                        o = i.y,
                        r = i.z;
                    return [s, o, r, -(s * t.x + o * t.y + r * t.z)];
                }
                CalPlaneLineIntersectPoint(e, t, n, a) {
                    var i, s, o, r, l, c, h, d, u, g, y, p, m, L, f = null;
                    return i = e.x, s = e.y, o = e.z, r = t.x, l = t.y, c = t.z, h = n.x, d = n.y, u = n.z, g = a.x, y = a.y, p = a.z, 0 == (L = h * i + d * s + u * o) ? f : (m = ((r - g) * i + (l - y) * s + (c - p) * o) / L, (f = new Laya.Vector3()).x = g + h * m, f.y = y + d * m, f.z = p + u * m, f);
                }
                getUnitVector(e, t) {
                    let n = Math.sqrt(Math.pow(e.x, 2) + Math.pow(e.y, 2) + Math.pow(e.z, 2)),
                        a = new Laya.Vector3();
                    return 0 == n ? a : (Laya.Vector3.scale(e, 1 / n * t, a), a);
                }
                limitNumberRange(e, t) {
                    return e < t[0] ? e = t[0] : e > t[1] && (e = t[1]), e;
                }
                getVector3ByTwoPoint(e, t) {
                    return new Laya.Vector3(t.x - e.x, t.y - e.y, t.z - e.z);
                }
                getDistanceByTwoPoint(e, t) {
                    return Math.sqrt(Math.pow(t.x - e.x, 2) + Math.pow(t.y - e.y, 2) + Math.pow(t.z - e.z, 2));
                }
                getAngleByTwoPointWithV2(e, t) {
                    let n = new Laya.Vector2(t.x - e.x, t.y - e.y),
                        a = Math.abs(n.x),
                        i = Math.abs(n.y);
                    if (0 == a) return n.y >= 0 ? 0 : 180;
                    if (n.x > 0 && n.y >= 0) {
                        let e = a / i;
                        return 180 / 3.14 * Math.atan(e);
                    }
                    if (n.x > 0 && n.y <= 0) {
                        let e = i / a;
                        return 90 + 180 / 3.14 * Math.atan(e);
                    }
                    if (n.x < 0 && n.y <= 0) {
                        let e = a / i;
                        return 180 + 180 / 3.14 * Math.atan(e);
                    } {
                        let e = i / a;
                        return 270 + 180 / 3.14 * Math.atan(e);
                    }
                }
                rectangleIntersect(e, t, n, a) {
                    let i = e.x,
                        s = e.y,
                        o = t.x,
                        r = t.y,
                        l = n.x,
                        c = n.y,
                        h = a.x,
                        d = a.y,
                        u = Math.abs(i + o - l - h),
                        g = Math.abs(i - o) + Math.abs(l - h),
                        y = Math.abs(s + r - c - d),
                        p = Math.abs(s - r) + Math.abs(c - d);
                    return u <= g && y <= p;
                }
                getOffsetByTwoPoint(e, t) {
                    return new Laya.Vector3(t.x - e.x, t.y - e.y, t.z - e.z);
                }
                triangulatePlanePolygon(e) {
                    if (e.length < 3) return null;
                    let t = [],
                        n = this.Vec3PlaneTransVec2Plane(e),
                        i = [],
                        s = this.getMinRectWithPoints(n.points);
                    i.push([s[0], s[1], s[2]]), i.push([s[0], s[2], s[3]]), n.points.sort((e, t) => e.x - t.x), this.insertPointsInTriangles(i, n.points);
                    for (var o = 0; o < i.length; o++)
                        for (var r = 0; r < i[o].length; r++)
                            if (i[o][r] == s[0] || i[o][r] == s[1] || i[o][r] == s[2] || i[o][r] == s[3]) {
                                i.splice(o, 1), o--;
                                break;
                            }
                    let l = this.getCoefficientByPlanes([n.ABC[0], n.ABC[1], n.ABC[2]]);
                    for (o = 0; o < i.length; o++) {
                        let e = [];
                        for (r = 0; r < i[o].length; r++) {
                            let t, s, c = i[o][r],
                                h = 0;
                            n.usexyz == a.Z ? (t = c.x, s = c.y, h = 0 == l[2] ? 0 : (l[0] * t + l[1] * s + l[3]) / -l[2]) : n.usexyz == a.Y ? (t = c.x, h = c.y, 0 == l[1] ? h = 0 : s = (l[0] * t + l[2] * h + l[3]) / -l[1]) : (h = c.x, s = c.y, 0 == l[0] ? h = 0 : t = (l[1] * s + l[2] * h + l[3]) / -l[0]), e.push(new Laya.Vector3(t, s, h));
                        }
                        t.push(e);
                    }
                    return t;
                }
                insertPointsInTriangles(e, t) {
                    for (var n = 0; n < t.length; n++) {
                        let o = t[n],
                            r = [];
                        for (var a = 0; a < e.length; a++) {
                            let t = e[a];
                            this.isPointInTriangle(this.vec2ToVec3(t[0]), this.vec2ToVec3(t[1]), this.vec2ToVec3(t[2]), this.vec2ToVec3(o)) && (r.push(e[a]), e.splice(a, 1), a--);
                        }
                        for (a = 0; a < r.length; a++) {
                            let t = r[a],
                                n = [],
                                l = this.getPositionByPointInLine(t[0], t[1], o);
                            0 != l && n.push([o, t[0], t[1]]), 0 != (l = this.getPositionByPointInLine(t[1], t[2], o)) && n.push([o, t[1], t[2]]), 0 != (l = this.getPositionByPointInLine(t[2], t[0], o)) && n.push([o, t[2], t[0]]);
                            for (var i = 0; i < n.length; i++) {
                                if (r.length > 1) {
                                    e.push(n[i]);
                                    continue;
                                }
                                let t = this.getTheSameEdgeData(e, [n[i][1], n[i][2], o]);
                                if (null == t) e.push(n[i]);
                                else {
                                    let a = this.getCircleData(t.triangle[0], t.triangle[1], t.triangle[2]);
                                    if (this.getDistanceByVec2(a.center, o) < a.radio) {
                                        for (var s = 0; s < e.length; s++)
                                            if (e[s] == t.triangle) {
                                                e.splice(s, 1);
                                                break;
                                            }
                                        let a = this.findSameEdgeTriangleCanCut(e, [t.point, n[i][1], o]);
                                        a || (a = this.findSameEdgeTriangleCanCut(e, [o, n[i][1], t.point])) || e.push([o, t.point, n[i][1]]), (a = this.findSameEdgeTriangleCanCut(e, [t.point, n[i][2], o])) || (a = this.findSameEdgeTriangleCanCut(e, [o, n[i][2], t.point])) || e.push([o, t.point, n[i][2]]);
                                    } else e.push(n[i]);
                                }
                            }
                        }
                    }
                }
                findSameEdgeTriangleCanCut(e, t) {
                    let n = this.getTheSameEdgeData(e, t);
                    if (null == n) return !1; {
                        let i = this.getCircleData(n.triangle[0], n.triangle[1], n.triangle[2]);
                        if (this.getDistanceByVec2(i.center, t[2]) < i.radio) {
                            for (var a = 0; a < e.length; a++)
                                if (e[a] == n.triangle) {
                                    e.splice(a, 1);
                                    break;
                                }
                            let i = this.findSameEdgeTriangleCanCut(e, [n.point, t[0], t[2]]);
                            return i || (i = this.findSameEdgeTriangleCanCut(e, [t[2], t[0], n.point])) || e.push([t[2], n.point, t[0]]), (i = this.findSameEdgeTriangleCanCut(e, [n.point, t[1], t[2]])) || (i = this.findSameEdgeTriangleCanCut(e, [t[2], t[1], n.point])) || e.push([t[2], n.point, t[1]]), !0;
                        }
                        return !1;
                    }
                }
                getMinRectWithPoints(e) {
                    let t, n, a, i = 0;
                    for (var s = 0; s < e.length; s++) 0 == s ? (t = n = e[s].x, a = i = e[s].y) : (e[s].x < t ? t = e[s].x : e[s].x > n && (n = e[s].x), e[s].y < a ? a = e[s].y : e[s].y > i && (i = e[s].y));
                    return [new Laya.Vector2(t - .1, a - .1), new Laya.Vector2(t - .1, i + .1), new Laya.Vector2(n + .1, i + .1), new Laya.Vector2(n + .1, a - .1)];
                }
                getTheSameEdgeData(e, t) {
                    for (var n in e) {
                        let a = this.isSameAsEdge([e[n][0], e[n][1]], t);
                        if (a) return new i(e[n], e[n][2], [e[n][0], e[n][1]], Number(n));
                        if (a = this.isSameAsEdge([e[n][1], e[n][2]], t)) return new i(e[n], e[n][0], [e[n][1], e[n][2]], Number(n));
                        if (a = this.isSameAsEdge([e[n][2], e[n][0]], t)) return new i(e[n], e[n][1], [e[n][2], e[n][0]], Number(n));
                    }
                    return null;
                }
                isSameAsEdge(e, t) {
                    let n = 0 == this.getDistanceByVec2(e[0], t[0]) || 0 == this.getDistanceByVec2(e[0], t[1]),
                        a = 0 == this.getDistanceByVec2(e[1], t[0]) || 0 == this.getDistanceByVec2(e[1], t[1]);
                    return n && a;
                }
                isPointInTriangle(e, t, n, a) {
                    let i = new Laya.Vector3(n.x - e.x, n.y - e.y, n.z - e.z),
                        s = new Laya.Vector3(t.x - e.x, t.y - e.y, t.z - e.z),
                        o = new Laya.Vector3(a.x - e.x, a.y - e.y, a.z - e.z),
                        r = Laya.Vector3.dot(i, i),
                        l = Laya.Vector3.dot(i, s),
                        c = Laya.Vector3.dot(i, o),
                        h = Laya.Vector3.dot(s, s),
                        d = Laya.Vector3.dot(s, o),
                        u = 1 / (r * h - l * l),
                        g = (h * c - l * d) * u;
                    if (g < 0 || g > 1) return !1;
                    let y = (r * d - l * c) * u;
                    return !(y < 0 || y > 1) && g + y <= 1;
                }
                vec2ToVec3(e) {
                    return new Laya.Vector3(e.x, e.y, 0);
                }
                getCircleData(e, t, n) {
                    let a, i, o, r, l, c;
                    a = e.x, i = t.x, o = n.x, r = e.y, l = t.y, c = n.y;
                    let h = Math.sqrt((a - i) * (a - i) + (r - l) * (r - l)),
                        d = Math.sqrt((a - o) * (a - o) + (r - c) * (r - c)),
                        u = Math.sqrt((i - o) * (i - o) + (l - c) * (l - c)),
                        g = (h + d + u) / 2,
                        y = h * d * u / (4 * Math.sqrt(g * (g - h) * (g - d) * (g - u))),
                        p = a * a + r * r,
                        m = i * i + l * l,
                        L = o * o + c * c,
                        f = a * l + i * c + o * r - a * c - i * r - o * l,
                        I = (m * c + p * l + L * r - m * r - L * l - p * c) / f / 2,
                        S = (L * i + m * a + p * o - p * i - m * o - L * a) / f / 2,
                        v = new Laya.Vector2(I, S);
                    return new s(v, y);
                }
                getDistanceByVec2(e, t) {
                    return Math.sqrt(Math.pow(t.x - e.x, 2) + Math.pow(t.y - e.y, 2));
                }
                getPositionByPointInLine(e, t, n) {
                    var a = (e.y - t.y) * n.x + (t.x - e.x) * n.y + e.x * t.y - t.x * e.y;
                    return a > 0 ? -1 : 0 == a ? 0 : 1;
                }
                isSameDirectionByPlane(e, t) {
                    return !(0 != e.x && 0 != t.x && e.x / t.x < 0) && (!(0 != e.y && 0 != t.y && e.y / t.y < 0) && !(0 != e.z && 0 != t.z && e.z / t.z < 0));
                }
                getDirectionByTriangle(e, t, n) {
                    let a = e.x,
                        i = e.y,
                        s = e.z,
                        o = t.x,
                        r = t.y,
                        l = t.z,
                        c = n.x,
                        h = n.y,
                        d = n.z,
                        u = a * (r * d - l * h) + i * (l * c - o * d) + s * (o * h - r * c);
                    return u > 0 ? 1 : u < 0 ? -1 : 0;
                }
                Vec3PlaneTransVec2Plane(e) {
                    let t = [],
                        n = this.getPlanePoints(e),
                        i = this.getNormalVectorByPlane([n[0], n[1], n[2]]),
                        s = a.Z;
                    s = 0 != i.x || 0 != i.y || 0 != i.z ? 0 != i.x ? a.X : 0 != i.y ? a.Y : a.Z : a.Z;
                    for (var r = 0; r < e.length; r++) s == a.Z ? t.push(new Laya.Vector2(e[r].x, e[r].y)) : s == a.Y ? t.push(new Laya.Vector2(e[r].x, e[r].z)) : t.push(new Laya.Vector2(e[r].z, e[r].y));
                    return new o(n, s, t);
                }
                getDistanceByPointToLine(e, t, n, a, i, s, o) {
                    return Math.abs(a * e + i * t + s * n + o) / Math.abs(a * a + i * i + s * s);
                }
                rangeRand(e) {
                    let t = Math.random(),
                        n = Math.abs(e[1] - e[0]);
                    return (e[0] < e[1] ? e[0] : e[1]) + n * t;
                }
                bigDataString(e) {
                    if (e < 1e3) return e % 1 != 0 && e.toFixed(2), "" + e;
                    let t = 1;
                    for (; t < 2 && !(e >= Math.pow(1e3, t) && e < Math.pow(1e3, t + 1));) t++;
                    let n = e / Math.pow(1e3, t);
                    return n % 1 != 0 && n.toFixed(2), "" + n + ["", "K", "B"][t > 2 ? 2 : t];
                }
            }
            r.instance = null, e.MathToolIns = r.getInstance();
            e.CollectData = class {
                constructor() {
                    this.count = 6, this.addCount = 1, this.texture = "", this.par = null, this.startPos = new Laya.Vector2(), this.endPos = new Laya.Vector2(), this.pathLength = 100, this.endCallback = null, this.isBessel = !0, this.frameDelay = 1, this.size = null;
                }
            };
            e.DropData = class {
                constructor() {
                    this.xRange = 750, this.everyCount = 6, this.frameCount = 10, this.tex = [], this.useGravity = !0, this.gravity = -9.8, this.rotateSpeed = 1, this.par = null, this.worldRotaSpeedRange = [0, 360], this.worldRotaDisRange = [0, 60], this.scaleRange = [.5, 1], this.continuedTime = -1;
                }
            };
            e.DiffusionData = class {
                constructor() {
                    this.xRange = 750, this.angleRange = [0, 360], this.everyCount = 6, this.frameCount = 10, this.tex = [], this.moveSpeed = 1, this.rotateSpeed = 1, this.par = null, this.scale = 1, this.pos = new Laya.Vector2();
                }
            };
            e.FluorescenceData = class {
                constructor() {
                    this.tex = [], this.par = null, this.range = [-300, 300], this.moveSpeed = 1, this.scaleRange = [.2, 1], this.alphaRange = [.2, 1];
                }
            };
            class l {
                constructor() { }
                static getInstance() {
                    return null == l.instance && (l.instance = new l()), l.instance;
                }
                creatrCollectView(t) {
                    var n = this;
                    Laya.loader.load(t.texture, Laya.Handler.create(n, () => {
                        if (e.LanguageToolIns.isNull(t.par) || e.LanguageToolIns.isNull(t.par.parent)) return;
                        let a = Math.floor(t.count / t.addCount),
                            i = null,
                            s = null,
                            o = 0;
                        for (let r = 0; r < a; r++) {
                            let l = new Laya.Image(t.texture);
                            l.anchorX = .5, l.anchorY = .5, l.x = t.startPos.x, l.y = t.startPos.y, t.size && l.scale(t.size.x, t.size.y), l.zOrder = 100, t.par.addChild(l);
                            let c = [];
                            if (t.isBessel) {
                                let n = 360 * Math.random(),
                                    a = e.MathToolIns.pointRotateByOtherPoint(t.startPos, new Laya.Vector2(t.startPos.x, t.startPos.y + 100), n);
                                i = a, n = 360 * Math.random(), s = a = e.MathToolIns.pointRotateByOtherPoint(t.startPos, new Laya.Vector2(t.startPos.x, t.startPos.y + 200), n);
                            } else i = s = new Laya.Vector2((t.startPos.x + t.endPos.x) / 2, (t.startPos.y + t.endPos.y) / 2);
                            e.MathToolIns.ComputeBezier([t.startPos, i, s, t.endPos], t.pathLength, c);
                            let h = {
                                index: 0
                            },
                                d = 0;
                            if (r != a - 1) d = t.addCount;
                            else {
                                let e = t.count % t.addCount;
                                d = t.addCount + e;
                            }
                            let u = () => {
                                e.LanguageToolIns.isNull(l) || e.LanguageToolIns.isNull(l.parent) || (h.index++, h.index >= c.length ? (l.clearTimer(n, u), l.destroy(), o++, null != t.endCallback && t.endCallback(d, o >= a)) : (l.x = c[h.index].x, l.y = c[h.index].y));
                            };
                            l.frameOnce(r * t.frameDelay, n, () => {
                                e.LanguageToolIns.isNull(l) || e.LanguageToolIns.isNull(l.parent) || l.frameLoop(1, n, u);
                            });
                        }
                    }));
                }
                addDropParticle(t) {
                    var n = this;
                    let a = 0,
                        i = t.frameCount,
                        s = () => {
                            if (!e.LanguageToolIns.isNull(t.par) && !e.LanguageToolIns.isNull(t.par.parent))
                                if (-1 != t.continuedTime && (a += Laya.timer.delta) >= t.continuedTime) t.par.clearTimer(n, s);
                                else if (!(++i < t.frameCount))
                                    if (i = 0, null != t.par.parent)
                                        for (var o = 0; o < t.everyCount; o++) {
                                            let a = Math.random(),
                                                i = Math.floor(a * t.tex.length);
                                            Laya.loader.load(t.tex[i], Laya.Handler.create(n, () => {
                                                if (e.LanguageToolIns.isNull(t.par) || e.LanguageToolIns.isNull(t.par.parent)) return;
                                                let s = Laya.Pool.getItemByClass(t.tex[i], Laya.Image);
                                                s.name = t.tex[i], s.source = Laya.loader.getRes(t.tex[i]), s.anchorX = .5, s.anchorY = .5, a = Math.random(), s.x = a * t.xRange, a = Math.random(), s.y = 100 * -a, a = Math.random(), s.rotation = 360 * a * t.rotateSpeed;
                                                let o = e.MathToolIns.rangeRand(t.scaleRange);
                                                s.scaleX = o, s.scaleY = o, t.par.addChild(s);
                                                let r = 0,
                                                    l = new Laya.Vector2(s.x, s.y),
                                                    c = 0,
                                                    h = e.MathToolIns.rangeRand(t.worldRotaSpeedRange),
                                                    d = e.MathToolIns.rangeRand(t.worldRotaDisRange),
                                                    u = () => {
                                                        if (null == s || null == s.parent || s.y >= e.ThirdPartyToolIns.getScreenSize().y) return s.clearTimer(n, u), void s.destroy();
                                                        r += e.AboutLayaToolIns.getTimerDelta() / 1e3;
                                                        let a = t.gravity;
                                                        t.useGravity && (a = .5 * t.gravity * r * r * 32), l.y = l.y + -a, c += h;
                                                        let i = e.MathToolIns.pointRotateByOtherPoint(l, new Laya.Vector2(l.x, l.y - d), c);
                                                        s.x = i.x, s.y = i.y, s.rotation += t.rotateSpeed;
                                                    };
                                                s.frameLoop(1, n, u);
                                            }));
                                        } else t.par.clearTimer(n, s);
                        };
                    t.par.frameLoop(1, n, s);
                }
                addDiffusionParticle(t) {
                    var n = this;
                    let a = () => {
                        if (null != t.par.parent)
                            for (var i = 0; i < t.everyCount; i++) {
                                let a = Math.random(),
                                    i = Math.floor(a * t.tex.length);
                                Laya.loader.load(t.tex[i], Laya.Handler.create(n, () => {
                                    let s = new Laya.Image();
                                    s.name = t.tex[i], e.AboutLayaToolIns.setSkin(s, t.tex[i]), s.anchorX = .5, s.anchorY = .5, null != t.pos ? (s.x = t.pos.x, s.y = t.pos.y) : (s.x = 0, s.y = 0), s.scaleX = t.scale, s.scaleY = t.scale, a = Math.random();
                                    let o = new Laya.Vector2(0, 1 * t.moveSpeed),
                                        r = a * (t.angleRange[1] - t.angleRange[0]) + t.angleRange[0];
                                    o = e.MathToolIns.pointRotateByOtherPoint(new Laya.Vector2(0, 0), o, r), a = Math.random(), s.rotation = 360 * a * t.rotateSpeed, t.par.addChild(s), s.alpha = 1, a = Math.random() * (t.xRange / 2) + t.xRange / 2;
                                    let l = t.moveSpeed / a,
                                        c = () => {
                                            if (null == s || null == s.parent || s.alpha <= 0) return s.clearTimer(n, c), void s.destroy();
                                            s.x += o.x, s.y += o.y, s.rotation += t.rotateSpeed, s.alpha -= l;
                                        };
                                    s.frameLoop(1, n, c);
                                }));
                            } else t.par.clearTimer(n, a);
                    };
                    t.par.frameLoop(t.frameCount, n, a);
                }
                addFluorescence(t) {
                    for (var n = this, a = 0; a < t.count; a++) {
                        let a = Math.floor(Math.random() * t.tex.length);
                        Laya.loader.load(t.tex[a], Laya.Handler.create(n, () => {
                            let i = new Laya.Image();
                            i.name = t.tex[a], e.AboutLayaToolIns.setSkin(i, t.tex[a]), i.anchorX = .5, i.anchorY = .5, i.x = e.MathToolIns.rangeRand(t.range), i.y = e.MathToolIns.rangeRand(t.range);
                            let s = new Laya.Vector2(1 * t.moveSpeed, 1 * t.moveSpeed);
                            s = e.MathToolIns.pointRotateByOtherPoint(new Laya.Vector2(0, 0), s, 360 * Math.random());
                            let o = Math.random() > .5 ? .01 : -.01;
                            i.scaleX = i.scaleY = e.MathToolIns.rangeRand(t.scaleRange);
                            let r = Math.random() > .5 ? .01 : -.01;
                            i.alpha = e.MathToolIns.rangeRand(t.alphaRange), t.par.addChild(i);
                            let l = () => {
                                null != i.parent ? (i.x += s.x, i.y += s.y, (i.x > t.range[1] || i.x < t.range[0]) && (s.x = -s.x), (i.y > t.range[1] || i.y < t.range[0]) && (s.y = -s.y), i.scaleX = i.scaleY = i.scaleX + o, (i.scaleX > t.scaleRange[1] || i.scaleX < t.scaleRange[0]) && (o = -o), i.alpha += r, (i.alpha > t.scaleRange[1] || i.alpha < t.scaleRange[0]) && (r = -r)) : i.clearTimer(n, l);
                            };
                            i.frameLoop(1, n, l);
                        }));
                    }
                }
            }
            l.instance = null, e.UiToolIns = l.getInstance();
            class c {
                constructor() { }
                static getInstance() {
                    return null == c.instance && (c.instance = new c()), c.instance;
                }
                shieldDownTouch(e) {
                    e.on(Laya.Event.MOUSE_DOWN, this, e => {
                        e.stopPropagation();
                    });
                }
                shieldUpTouch(e) {
                    e.on(Laya.Event.MOUSE_UP, this, e => {
                        e.stopPropagation();
                    });
                }
                creatorShieldTouchView(t) {
                    let n = t.getChildByName("vi_shieldTouch");
                    if (null != n) return;
                    let a = e.ThirdPartyToolIns.getScreenSize();
                    (n = new Laya.View()).name = "vi_shieldTouch", n.width = a.x, n.height = a.y, n.zOrder = 100, t.addChild(n), n.on(Laya.Event.MOUSE_UP, this, e => {
                        e.stopPropagation();
                    });
                }
                removeShieldTouchView(e) {
                    let t = e.getChildByName("vi_shieldTouch");
                    null != t && t.destroy();
                }
                setSkin(t, n) {
                    Laya.loader.load(n, Laya.Handler.create(this, () => {
                        if (e.LanguageToolIns.isNull(t) || e.LanguageToolIns.isNull(t.parent)) return;
                        let a = Laya.loader.getRes(n);
                        t instanceof Laya.Image ? t.source = a : t.texture = a;
                    }));
                }
                WorldToScreen(e, t) {
                    var n = t.transform,
                        a = this.InverseTransformPoint(n, e),
                        i = a.z,
                        s = .5 * t.fieldOfView * Math.PI / 180,
                        o = i * Math.tan(s),
                        r = o * t.aspectRatio,
                        l = new Laya.Vector3(),
                        c = new Laya.Vector3();
                    n.getRight(c);
                    var h = new Laya.Vector3(c.x * r, c.y * r, c.z * r);
                    Laya.Vector3.subtract(n.position, h, l);
                    var d = new Laya.Vector3();
                    n.getUp(d);
                    var u = new Laya.Vector3(d.x * o, d.y * o, d.z * o);
                    Laya.Vector3.subtract(l, u, l);
                    var g = new Laya.Vector3();
                    n.getForward(g);
                    var y = new Laya.Vector3(-g.x * i, -g.y * i, -g.z * i);
                    Laya.Vector3.add(l, y, l);
                    var p = new Laya.Vector3();
                    p.x = Laya.stage.width / r / 2, p.y = Laya.stage.height / o / 2, p.z = 0;
                    var m = new Laya.Vector3(),
                        L = this.InverseTransformPoint(n, l);
                    return Laya.Vector3.subtract(a, L, m), m = new Laya.Vector3(m.x * p.x, m.y * p.y, a.z);
                }
                ScreenToWorld(e, t) {
                    var n = e.z,
                        a = .5 * t.fieldOfView * Math.PI / 180,
                        i = n * Math.tan(a),
                        s = i * t.aspectRatio,
                        o = new Laya.Vector3(),
                        r = t.transform,
                        l = new Laya.Vector3();
                    r.getRight(l);
                    var c = new Laya.Vector3(l.x * s, l.y * s, l.z * s);
                    Laya.Vector3.subtract(r.position, c, o);
                    var h = new Laya.Vector3();
                    r.getUp(h);
                    var d = new Laya.Vector3(h.x * i, h.y * i, h.z * i);
                    Laya.Vector3.subtract(o, d, o);
                    var u = new Laya.Vector3();
                    r.getForward(u);
                    var g = new Laya.Vector3(-u.x * n, -u.y * n, -u.z * n);
                    Laya.Vector3.add(o, g, o);
                    var y = new Laya.Vector3();
                    y.x = s / Laya.stage.width * e.x * 2, y.y = i / Laya.stage.height * e.y * 2, y.z = 0;
                    var p = new Laya.Vector3();
                    return o = this.InverseTransformPoint(r, o), Laya.Vector3.add(o, y, p), p = this.TransformPoint(r, p);
                }
                InverseTransformPoint(e, t) {
                    var n = new Laya.Vector3();
                    e.getRight(n);
                    var a = new Laya.Vector3();
                    e.getUp(a);
                    var i = new Laya.Vector3();
                    e.getForward(i);
                    var s = new Laya.Vector3(-i.x, -i.y, -i.z),
                        o = this.ProjectDistance(t, e.position, n),
                        r = this.ProjectDistance(t, e.position, a),
                        l = this.ProjectDistance(t, e.position, s);
                    return new Laya.Vector3(o, r, l);
                }
                TransformPoint(e, t) {
                    var n = new Laya.Vector3();
                    return Laya.Vector3.transformQuat(t, e.rotation, n), Laya.Vector3.add(n, e.position, n), n;
                }
                ProjectDistance(e, t, n) {
                    var a = new Laya.Vector3();
                    Laya.Vector3.subtract(e, t, a);
                    var i = this.Angle(a, n) * Math.PI / 180,
                        s = Laya.Vector3.distance(e, t);
                    return s *= Math.cos(i);
                }
                Angle(e, t) {
                    var n = (e.x * t.x + e.y * t.y + e.z * t.z) / (Math.sqrt(e.x * e.x + e.y * e.y + e.z * e.z) * Math.sqrt(t.x * t.x + t.y * t.y + t.z * t.z));
                    return 180 * Math.acos(n) / Math.PI;
                }
                toTarPos(e, t) {
                    let n = e.transform.position;
                    e.transform.translate(new Laya.Vector3(t.x - n.x, t.y - n.y, t.z - n.z), !1);
                }
                moveToTarPos(t, n, a, i, s) {
                    let o = () => {
                        if (null == t[0].parent) return void t[0].clearTimer(this, o);
                        let r = t[0].transform.position;
                        if (e.MathToolIns.getDistanceByTwoPoint(r, n) >= e.MathToolIns.getDistanceByTwoPoint(a, new Laya.Vector3(0, 0, 0))) {
                            for (var l = 0; l < t.length; l++) t[l].transform.translate(a, !1);
                            if (null != i && i()) return void t[0].clearTimer(this, o);
                        } else {
                            let a = e.MathToolIns.getOffsetByTwoPoint(r, n);
                            for (l = 0; l < t.length; l++) t[l].transform.translate(a, !1);
                            null != s && s(), t[0].clearTimer(this, o);
                        }
                    };
                    o(), t[0].frameLoop(1, this, o);
                }
                screenPosToWorld(e, t, n, a) {
                    let i = new Laya.Ray(new Laya.Vector3(), new Laya.Vector3()),
                        s = [];
                    e.viewportPointToRay(n, i), t.physicsSimulation.rayCastAll(i, s);
                    for (var o = 0; o < s.length; o++)
                        if (s[o].collider.owner.name == a) {
                            return new Laya.Vector3(s[o].point.x, s[o].point.y, s[o].point.z);
                        }
                    return null;
                }
                particle3dDestroyByPlayEnd(e) {
                    let t = 0;
                    for (var n = 0; n < e.numChildren; n++) {
                        let a = e.getChildAt(n);
                        a.particleSystem.duration > t && (t = a.particleSystem.duration);
                    }
                    return e.timerOnce(1e3 * t * 2, this, () => {
                        e.destroy();
                    }), 1e3 * t;
                }
                particle3dRecoverByPlayEnd(e) {
                    let t = 0;
                    for (var n = 0; n < e.numChildren; n++) {
                        let a = e.getChildAt(n);
                        a.particleSystem.duration > t && (t = a.particleSystem.duration);
                    }
                    return e.timerOnce(1e3 * t * 2, this, () => {
                        e.removeSelf(), Laya.Pool.recover(e.name, e);
                    }), 1e3 * t;
                }
                baseAttrClone(e, t) {
                    let n = ["name", "skin", "x", "y", "width", "height", "left", "right", "top", "bottom", "centerX", "centerY", "anchorX", "anchorY", "scaleX", "scaleY", "rotation"];
                    for (var a = 0; a < n.length; a++) t[n[a]] = e[n[a]];
                }
                attrClone(e, t, n) {
                    this.baseAttrClone(e, t);
                    for (var a = 0; a < n.length; a++) t[n[a]] = e[n[a]];
                    for (a = 0; a < e.numChildren; a++) {
                        let n = e.getChildAt(a);
                        if (n instanceof Laya.Button) {
                            let e = this.cloneButton(n);
                            t.addChild(e);
                        } else if (n instanceof Laya.FontClip) {
                            let e = this.cloneFontClip(n);
                            t.addChild(e);
                        } else if (n instanceof Laya.Image) {
                            let e = this.cloneImage(n);
                            t.addChild(e);
                        } else if (n instanceof Laya.Label) {
                            let e = this.cloneLabel(n);
                            t.addChild(e);
                        } else if (n instanceof Laya.View) {
                            let e = this.cloneView(n);
                            t.addChild(e);
                        }
                    }
                }
                cloneImage(e) {
                    let t = new Laya.Image();
                    return this.attrClone(e, t, []), t;
                }
                cloneFontClip(e) {
                    let t = new Laya.FontClip();
                    return this.attrClone(e, t, ["align", "sheet", "spaceX", "direction"]), t;
                }
                cloneLabel(e) {
                    let t = new Laya.Label();
                    return this.attrClone(e, t, ["text", "bold", "font", "fontSize", "color", "align", "valign", "overflow"]), t;
                }
                cloneButton(e) {
                    let t = new Laya.Button();
                    return this.attrClone(e, t, ["stateNum", "selected"]), t;
                }
                cloneView(e) {
                    let t = new Laya.View();
                    return this.attrClone(e, t, []), t;
                }
                getTimerDelta() {
                    let e = Laya.timer.delta;
                    return e >= 100 && (e = 16.6), e;
                }
                clearPoolByNames(e) {
                    for (var t = 0; t < e.length; t++) Laya.Pool.clearBySign(e[t]);
                }
            }
            c.instance = null, e.AboutLayaToolIns = c.getInstance();
            class h {
                constructor() {
                    this.musicIns = null;
                }
                static getInstance() {
                    return null == h.instance && (h.instance = new h()), h.instance;
                }
                getScreenSize() {
                    return new Laya.Vector2(Laya.stage.displayWidth, Laya.stage.displayHeight);
                }
                playMusic() {
                    null != this.musicIns && this.musicIns.play();
                }
                pauseMusic() {
                    null != this.musicIns && this.musicIns.pause();
                }
                stopMusic() {
                    null != this.musicIns && (this.musicIns.stop(), this.musicIns = null);
                }
                seekMusic(e) {
                    null != this.musicIns && this.musicIns.seek(e);
                }
            }
            h.instance = null, e.ThirdPartyToolIns = h.getInstance();
        }(w || (w = {}));
    class b {
        static CoinAni(t, n, a, i = null) {
            e.Instance.coinNum += t, A.saveData(v.coinNum, e.Instance.coinNum);
            ! function (e, t, n, i) {
                if (e <= 0) return;
                let s = new w.CollectData();
                s.texture = n, s.count = e, s.addCount = e <= 6 ? 1 : Math.floor(e / 6), s.par = a, s.startPos = new Laya.Vector2(375, 658), s.endPos = i, s.frameDelay = 1, s.pathLength = 50, s.endCallback = ((e, n) => {
                    n && t();
                }), w.UiToolIns.creatrCollectView(s);
            }(5, function () {
                n.value = e.Instance.coinNum.toString(), i && i.run();
            }, "UI/lobby/03_ks_cbklh.png", new Laya.Vector2(56, 112));
        }
    }
    class P extends S.Views.GameSceneUI {
        constructor() {
            super(...arguments), this.isDown = !1, this.t = .1;
        }
        onAwake() {
            P.instance = this, this.height = Laya.stage.height, this.playerSc = s.Instance.Player.getComponent(I), this.prefab = this.getComponent(_), this.on(Laya.Event.MOUSE_DOWN, this, this.onMouseDown), this.on(Laya.Event.MOUSE_OUT, this, this.onMouseUp), this.on(Laya.Event.MOUSE_UP, this, this.onMouseUp), this.tex_money.value = e.Instance.coinNum.toString(), Laya.timer.frameLoop(1, this, this.onUpdate), m.getInstance().showBannerNotCreat(0), p.reportEvent("GameLevelstart_" + e.Instance.currentLevel.toString()), p.AldStageOnStart({
                stageId: e.Instance.currentLevel.toString(),
                stageName: e.Instance.currentLevel.toString()
            });
        }
        onMouseUp() {
            this.isDown = !1;
        }
        onMouseDown() {
            0 == this.playerSc.isFinish && 1 == m.getInstance().setting.Lc_GameOverType || (this.isDown = !0, this.t = 0);
        }
        onUpdate() {
            this.isDown && (this.t -= .001 * Laya.timer.delta, this.t < 0 && (this.t = .1, this.playerSc.isFinish && 0 == N.Instance.isUpdatePicture && (this.showAnZhuTishi(), this.playerSc.flyPencil())));
        }
        addone(e, t) {
            let n = this.prefab.creatAddOne(new Laya.Vector2(e, t));
            this.addChild(n), n.pos(e, t), n.alpha = 1, Laya.Tween.to(n, {
                y: n.y - 200
            }, 1e3, Laya.Ease.strongOut, Laya.Handler.create(this, function () {
                n.removeSelf(), Laya.Pool.recover("addOne", n);
            }));
        }
        showAnZhuTishi() {
            this.sp_huahuatishi.visible = !0, this.handBox.visible = !1;
        }
        onDisable() {
            P.instance = null, Laya.timer.clearAll(this);
        }
        CompleteCoinAni() {
            b.CoinAni(e.Instance.completePictureCoin, this.tex_money, this);
        }
    }
    class N {
        constructor() {
            this._maxLevelNum = 6, this._isloading = !1, this.uvs = [], this.myuvs = [], this.uvsback = [], this.indexn = -1, this.randomArr = [], this.isUpdatePicture = !1, this.colorList = [], this.colorSpList = [], this.colorList2 = [], this.teshuColorID = 0, this.posID = 0, this.pictureScaleX = 3.4, this.pictureScaleY = 3.4, this.PictureArr = [
                [114, 115, 116, 117, 118, 119, 60, 61, 62, 63, 64, 65, 120, 24, 25, 26, 27, 28, 29, 36, 37, 38, 39, 40, 41, 96, 97, 98, 99, 100, 101, 48, 49, 50, 51, 52, 53, 42, 43, 44, 45, 46, 47, 54, 55, 56, 57, 58, 59, 78, 79, 80, 81, 82, 83, 108, 109, 110, 111, 112, 113, 72, 73, 74, 75, 76, 77, 90, 91, 92, 93, 94, 95, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 18, 19, 20, 21, 22, 23, 66, 67, 68, 69, 70, 71, 84, 85, 86, 87, 88, 89, 30, 31, 32, 33, 34, 35, 12, 13, 14, 15, 16, 17, 102, 103, 104, 105, 106, 107]
            ];
        }
        static get Instance() {
            return null == this._instance && (this._instance = new N()), this._instance;
        }
        loadLevel(t, n = e.Instance.currentLevel) {
            if ((n < 0 || n > this._maxLevelNum) && (n = i.MathTool.getRandomInt(this._maxLevelNum, 1)), this._isloading) return;
            e.Instance.realLevel = n, console.log("真实关卡", e.Instance.realLevel);
            let a = "res/UnityScene/Prefab/Conventional/level-" + n.toString() + ".lh";
            s.Instance.currentLevelSp && (s.Instance.currentLevelSp.destroy(!0), s.Instance.currentLevelSp = null, s.Instance.Player = null), this._isloading = !0, Laya.Sprite3D.load(a, Laya.Handler.create(this, this.loadComplete, [t]));
        }
        preloadLevel(t, n = e.Instance.currentLevel) {
            (n < 0 || n > this._maxLevelNum) && (n = i.MathTool.getRandomInt(this._maxLevelNum, 1)), e.Instance.realLevel = n;
            let a = "res/UnityScene/Prefab/Conventional/level-" + n.toString() + ".lh";
            Laya.loader.clearRes(a), Laya.Sprite3D.load(a, t);
        }
        loadLevelByPreload(e) {
            s.Instance.currentLevelSp && (s.Instance.currentLevelSp.destroy(!0), s.Instance.currentLevelSp = null, s.Instance.Player = null), this.loadComplete(null, e);
        }
        loadComplete(e, t) {
            s.Instance.Scene3D.addChild(t), s.Instance.currentLevelSp = t, this.teshuSp = s.Instance.currentLevelSp.getChildByName("[teshu]");
            let n = s.Instance.currentLevelSp.getChildByName("[PENSILS]");
            this.initColor(n), this.teshuSp && this.initTeShuPencil();
            let a = t.getChildByName("[POINTS]").getChildByName("player_finish_point").getChildByName("finish_trigger").transform.position,
                i = t.getChildByName("[POINTS]").getChildByName("player_finish_point").getChildByName("coloring_manager").getChildAt(1),
                o = Laya.Sprite3D.instantiate(s.Instance.pre_picture, i, !1);
            o.transform.position = new Laya.Vector3(o.transform.position.x, o.transform.position.y + .1, a.z + 8.6), s.Instance.currentPicture = o, s.Instance.current_pencil_case = i.parent.getChildAt(0).getChildAt(1), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildByName("pencil_case"), s.Instance.current_pencil_case).transform.localPosition = new Laya.Vector3(0, 0, 0), this.Over(o), this._isloading = !1, e && e.run();
        }
        Over(t) {
            this.indexn = -1, this.uvs = [], this.uvsback = [];
            let n = t.getChildAt(1);
            this.myuvs && n.meshFilter.sharedMesh.setUVs(this.myuvs), n.meshFilter.sharedMesh.getUVs(this.uvs), this.myuvs.length <= 0 && (this.myuvs = this.uvs.copyWithin(this.uvs.length, 0));
            for (let e = 0; e < this.uvs.length; e++) this.uvsback.push(new Laya.Vector2(-100, -100));
            console.log("模型uv", this.myuvs), this.model = n, this.model.meshFilter.sharedMesh.setUVs(this.uvsback), this.initRandom(), a.initShader();
            let s = new a();
            s.albedoTexture = null, n.meshRenderer.sharedMaterial = s, this.mat = s;
            let o = e.Instance.PictureData.currentPictureID;
            e.Instance.PictureData.currentPictureID > e.Instance.maxPicture && (o = i.MathTool.getRandomInt(e.Instance.maxPicture, 1)), this.setTexture("UI/texture/" + e.Instance.texture[o]), this.initProgress();
        }
        initProgress() {
            for (let t = 0; t < e.Instance.PictureData.currentPictureProgress; t++) this._update();
        }
        initRandom() {
            -1 == e.Instance.PictureData.currentRandomArr && (e.Instance.PictureData.currentRandomArr = i.MathTool.getRandomInt(this.PictureArr.length)), this.randomArr = this.PictureArr[e.Instance.PictureData.currentRandomArr], console.log(this.randomArr), console.log("数组长度", this.randomArr.length);
        }
        setTexture(e) {
            let t = this;
            Laya.Texture2D.load(e, Laya.Handler.create(this, function (e) {
                t.mat.albedoTexture = e;
            }));
        }
        initColor(e) {
            this.colorList = [new Laya.Vector4(0, .5170307, .8396226, 1), new Laya.Vector4(.02499998, .5, 0, 1), new Laya.Vector4(.4378916, 0, .8490566, 1), new Laya.Vector4(.8679245, .1842293, .390762, 1), new Laya.Vector4(.745283, 0, .07117879, 1), new Laya.Vector4(.8773585, .3251593, 0, 1), new Laya.Vector4(.764151, .5283856, 0, 1)], this.colorList2 = [new Laya.Vector4(0, .6694651, 1, 1), new Laya.Vector4(.3230592, .990566, .1074671, 1), new Laya.Vector4(.5857595, .2122642, 1, 1), new Laya.Vector4(1, .4292453, .517975, 1), new Laya.Vector4(1, .1811876, .08018869, 1), new Laya.Vector4(.8867924, .5053231, 0, 1), new Laya.Vector4(1, .8258382, 0, 1)], this.colorSpList = [];
            for (let t = 0; t < this.colorList.length; t++) {
                let n = [];
                for (let a = 0; a < e.numChildren; a++) {
                    let i = e.getChildAt(a).getChildAt(0).meshRenderer.sharedMaterial.albedoColor;
                    Laya.Vector4.equals(this.colorList[t], i) && n.push(e.getChildAt(a));
                }
                this.colorSpList.push(n);
            }
        }
        initTeShuPencil() {
            if (this.teshuSp && (this.teshuColorID = i.MathTool.getRandomInt(7), console.log("特殊皮肤", this.teshuColorID), this.teshuSp.numChildren > 0)) {
                let e = this.teshuSp.getChildAt(0);
                e.name = this.teshuColorID.toString();
                let t = e.getChildAt(0);
                t.meshRenderer.enable = !1, t.meshRenderer.materials[0].albedoColor = this.colorList[this.teshuColorID].clone(), t.meshRenderer.materials[1].albedoColor = this.colorList2[this.teshuColorID].clone();
                let n = t.getChildAt(0),
                    a = "res/pkg/teshuTexture/" + this.teshuColorID + ".png";
                Laya.Texture2D.load(a, Laya.Handler.create(this, function (e) {
                    n.meshRenderer.materials[0].albedoTexture = e, n.meshRenderer.materials[1].texture = e;
                }));
            }
        }
        Update() {
            if (!this.isUpdatePicture)
                if (this.indexn++, e.Instance.PictureData.currentPictureProgress = this.indexn, this.indexn >= this.uvs.length) {
                    this.isUpdatePicture = !0;
                    let t = this;
                    Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(5), s.Instance.currentLevelSp).transform.position = new Laya.Vector3(s.Instance.currentPicture.transform.position.x, s.Instance.currentPicture.transform.position.y, s.Instance.currentPicture.transform.position.z - 2), P.instance && P.instance.CompleteCoinAni();
                    let n = s.Instance.currentPicture.transform.localPosition.clone();
                    if (s.Instance.Player && s.Instance.Player.numChildren <= 0) return console.log("没有笔但完成了画"), -1 == e.Instance.album.haved.indexOf(e.Instance.PictureData.currentPictureID) && (e.Instance.album.haved.push(e.Instance.PictureData.currentPictureID), e.Instance.isHaveNewPicture = !0), e.Instance.PictureData.currentPictureID++, e.Instance.PictureData.currentPictureProgress = 0, void (e.Instance.PictureData.currentRandomArr = -1);
                    Laya.timer.once(3e3, this, function () {
                        i.AnimationTool.moveTo3d(s.Instance.currentPicture, new Laya.Vector3(-2, 0, n.z), 1e3, !0, Laya.Handler.create(this, function () {
                            Laya.timer.once(100, this, function () {
                                s.Instance.currentPicture.destroy(), s.Instance.currentPicture = null;
                                let a = s.Instance.currentLevelSp.getChildByName("[POINTS]").getChildAt(0).getChildAt(0).getChildAt(1),
                                    o = Laya.Sprite3D.instantiate(s.Instance.pre_picture.clone(), a, !1);
                                s.Instance.currentPicture = o, s.Instance.currentPicture.transform.localPosition = new Laya.Vector3(2, 0, n.z), i.AnimationTool.moveTo3d(s.Instance.currentPicture, new Laya.Vector3(n.x, 0, n.z), 1e3, !0, Laya.Handler.create(this, function () {
                                    -1 == e.Instance.album.haved.indexOf(e.Instance.PictureData.currentPictureID) && (e.Instance.album.haved.push(e.Instance.PictureData.currentPictureID), e.Instance.isHaveNewPicture = !0), e.Instance.PictureData.currentPictureID++, e.Instance.PictureData.currentPictureProgress = 0, e.Instance.PictureData.currentRandomArr = -1, t.Over(o), t.isUpdatePicture = !1;
                                }));
                            });
                        }));
                    });
                } else this.uvsback[this.randomArr[this.indexn]] = this.uvs[this.randomArr[this.indexn]], this.model.meshFilter.sharedMesh.setUVs(this.uvsback);
        }
        _update() {
            this.indexn++, this.indexn >= this.uvs.length || (this.uvsback[this.randomArr[this.indexn]] = this.uvs[this.randomArr[this.indexn]], this.model.meshFilter.sharedMesh.setUVs(this.uvsback));
        }
        getPos() {
            let e = new Laya.Vector3();
            this.posID = this.indexn + 1;
            let t = new Laya.Vector2();
            this.posID >= this.uvs.length || (t = this.uvs[this.randomArr[this.posID]]);
            let n = this.model.transform.position.x + this.pictureScaleX - t.x * this.pictureScaleX * 2,
                a = this.model.transform.position.y + this.pictureScaleY - t.y * this.pictureScaleY * 2,
                i = this.model.transform.position.z;
            return e.setValue(n, a, i), console.log(this.indexn), console.log(t), console.log(e), e;
        }
        changePicture(t = e.Instance.PictureData.currentPictureID, n = e.Instance.PictureData.currentPictureProgress) {
            this.setTexture("UI/texture/" + t.toString() + "_tg_cbklh.png");
            for (let e = 0; e < n; e++) this._update();
        }
        changeSpecialPencil(e, t) {
            console.log("colorID", t);
            for (let n = 0; n < e.length; n++) {
                let a = e[n].getChildAt(0);
                a.meshRenderer.enable = !1;
                let i = s.Instance.pre_specialPencil.clone(),
                    o = "res/pkg/teshuTexture/" + t + ".png";
                Laya.Texture2D.load(o, Laya.Handler.create(this, function (e) {
                    i.meshRenderer.materials[0].albedoTexture = e, i.meshRenderer.materials[1].texture = e;
                })), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(3), i).transform.localPosition = new Laya.Vector3(0, 0, 0), a.addChild(i), i.transform.localPosition = new Laya.Vector3(0, 0, 0), i.transform.localRotationEuler = new Laya.Vector3(0, 0, 0);
            }
            for (let e = 0; e < s.Instance.Player.numChildren; e++) {
                let n = s.Instance.Player.getChildAt(e).getChildAt(0).meshRenderer.materials[0].albedoColor;
                if (Laya.Vector4.equals(N.Instance.colorList[t], n)) {
                    let n = s.Instance.Player.getChildAt(e).getChildAt(0);
                    n.meshRenderer.enable = !1;
                    let a = s.Instance.pre_specialPencil.clone(),
                        i = "res/pkg/teshuTexture/" + t + ".png";
                    Laya.Texture2D.load(i, Laya.Handler.create(this, function (e) {
                        a.meshRenderer.materials[0].albedoTexture = e, a.meshRenderer.materials[1].texture = e;
                    })), Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildAt(3), a).transform.localPosition = new Laya.Vector3(0, 0, 0), n.addChild(a), a.transform.localPosition = new Laya.Vector3(0, 0, 0), a.transform.localRotationEuler = new Laya.Vector3(0, 0, 0);
                }
            }
        }
        updateSkin(t = e.Instance.Skin.mySkin) {
            t < 0 || this.colorSpList.length >= t || this.changeSpecialPencil(this.colorSpList[t], t);
        }
        updateBG() {
            let t = "res/pkg/bg/0" + (e.Instance.currentLevel % 3 + 1).toString() + "bg_cbklh.png";
            s.Instance.Bg ? s.Instance.Bg.skin = t : (s.Instance.Bg = new Laya.Image(t), s.Instance.Bg.width = 750, s.Instance.Bg.height = Laya.stage.height, s.Instance.Bg.zOrder = -10, Laya.stage.addChildAt(s.Instance.Bg, 0));
        }
    }
    N._instance = null;
    class E extends S.Views.FailSceneUI {
        constructor() {
            super(...arguments), this.failCoin = 0, this.nextLevel = null;
        }
        onAwake() {
            let t = this;
            this.height = Laya.stage.height, this.failCoin = e.Instance.failCoinNum, this.tex_level.text = e.Instance.currentLevel.toString(), this.tex_money.value = e.Instance.coinNum.toString(), this.tex_failCoin.text = this.failCoin.toString(), A.saveData(v.newUser, "false"), N.Instance.preloadLevel(Laya.Handler.create(this, function (e) {
                t.nextLevel = e, t.btn_restart.once(Laya.Event.CLICK, t, t.onRestart), console.log("预加载完成", e);
            })), e.Instance.Skin.mySkin = -1, m.getInstance().hideBanner(), p.reportEvent("NewGame_Failed"), p.reportEvent("GameLevelover_" + e.Instance.currentLevel.toString()), p.reportEvent("GameOver"), p.reportEvent("GameOverfailed"), p.AldStageOnEnd({
                stageId: e.Instance.currentLevel.toString(),
                stageName: e.Instance.currentLevel.toString(),
                event: "fail"
            });
            platform.getInstance().showInterstitial();

        }
        onRestart() {
            let e = this;
            b.CoinAni(e.failCoin, this.tex_money, this, Laya.Handler.create(this, function () {
                e.nextLevel && (N.Instance.loadLevelByPreload(e.nextLevel), Laya.Scene.open(c.LobbyScene));
            })), p.reportEvent("NewGame_FailedRestart");
        }
    }
    class D extends Laya.Script {
        onAwake() {
            this.btn = this.owner, this.currentScale = new Laya.Vector2(this.btn.scaleX, this.btn.scaleY);
        }
        onMouseDown() {
            Laya.Tween.to(this.btn, {
                scaleX: .8 * this.currentScale.x,
                scaleY: .8 * this.currentScale.y
            }, 100, Laya.Ease.quartOut, Laya.Handler.create(this, function () { }));
        }
        onMouseUp() {
            Laya.Tween.to(this.btn, {
                scaleX: this.currentScale.x,
                scaleY: this.currentScale.y
            }, 100, Laya.Ease.quartOut, Laya.Handler.create(this, function () { }));
        }
        onMouseOut() {
            Laya.Tween.to(this.btn, {
                scaleX: this.currentScale.x,
                scaleY: this.currentScale.y
            }, 100, Laya.Ease.quartOut, Laya.Handler.create(this, function () { }));
        }
    }
    class T extends r.LoadingScene {
        onAwake() {
            this.DebugLog(), A.loadData(), this.owner.once("awake", this, this.awake);
            let e = this;
            super.onAwake(), e.owner.event("awake");
        }
        awake() {
            super.onLoad(), console.log("awake"), this.text_Loading = this.owner.getChildByName("tex_loading"), this.text_Loading.y = Laya.stage.height - 270;
        }
        DebugLog() { }
    }
    class M extends S.Views.LobbySceneUI {
        onVideo(t, n) {
            let a = this,
                i = !1;
            switch (t) {
                case 1:
                    e.Instance.intensify.pencilNum < e.Instance.intensify_PencilNum.length && e.Instance.coinNum < e.Instance.intensify_PencilNum[e.Instance.intensify.pencilNum - 1][1] && (i = !0);
                    break;
                case 2:
                    e.Instance.intensify.coinIntensify < e.Instance.intensify_Coin.length && e.Instance.coinNum < e.Instance.intensify_Coin[e.Instance.intensify.coinIntensify - 1][1] && (i = !0);
                    break;
                case 3:
                    e.Instance.intensify.pencilLossIntensify < e.Instance.intensify_PencilLoss.length && e.Instance.coinNum < e.Instance.intensify_PencilLoss[e.Instance.intensify.pencilLossIntensify - 1][1] && (i = !0);
            }
            i && this.showTishi();
            n(function () {
                if (!i) {
                    switch (t) {
                        case 1:
                            e.Instance.intensify.pencilNum < e.Instance.intensify_PencilNum.length && (e.Instance.coinNum >= e.Instance.intensify_PencilNum[e.Instance.intensify.pencilNum - 1][1] && (e.Instance.coinNum -= e.Instance.intensify_PencilNum[e.Instance.intensify.pencilNum - 1][1]), e.Instance.intensify.pencilNum++, a.playerSc.addPencilQianghua()), p.reportEvent("GameLvUpLife");
                            break;
                        case 2:
                            e.Instance.intensify.coinIntensify < e.Instance.intensify_Coin.length && (e.Instance.coinNum >= e.Instance.intensify_Coin[e.Instance.intensify.coinIntensify - 1][1] && (e.Instance.coinNum -= e.Instance.intensify_Coin[e.Instance.intensify.coinIntensify - 1][1]), e.Instance.intensify.coinIntensify++), p.reportEvent("GameLvUpGold");
                            break;
                        case 3:
                            e.Instance.intensify.pencilLossIntensify < e.Instance.intensify_PencilLoss.length && (e.Instance.coinNum >= e.Instance.intensify_PencilLoss[e.Instance.intensify.pencilLossIntensify - 1][1] && (e.Instance.coinNum -= e.Instance.intensify_PencilLoss[e.Instance.intensify.pencilLossIntensify - 1][1]), e.Instance.intensify.pencilLossIntensify++), p.reportEvent("GameLvUpDraw");
                    }
                    a.updateIntensify();
                }
            }, !1);
        }
        onAwake() {
            this.height = Laya.stage.height, this.btn_start.height = Laya.stage.height, this.initBtnEvent(), this.creatPlayer(), this.updateIntensify(), e.Instance.isNewUser && e.Instance.currentLevel <= 1 && (this.btn_pencil.visible = !1, this.Intensify.visible = !1, this.btn_picture.visible = !1), N.Instance.updateBG(), m.getInstance().hideBanner(), p.reportEvent("NewGame_FingerGuid");
            this.btn_music.skin = Laya.SoundManager.muted ? "UI/lobby/btn_sound_off.png" : "UI/lobby/btn_sound_on.png";
            this.btn_showInt.visible = false;
        }
        initBtnEvent() {
            this.btn_showInt.on(Laya.Event.MOUSE_DOWN, this, this.onShowInt), this.btn_music.on(Laya.Event.CLICK, this, this.changeMusic), this.btn_start.on(Laya.Event.MOUSE_DOWN, this, this.onStartGame), this.btn_picture.on(Laya.Event.CLICK, this, this.onOpenPicture), this.btn_pencil.on(Laya.Event.CLICK, this, this.onOpenSkin);
        }
        changeMusic() {
            Laya.SoundManager.muted = !Laya.SoundManager.muted;
            this.btn_music.skin = Laya.SoundManager.muted ? "UI/lobby/btn_sound_off.png" : "UI/lobby/btn_sound_on.png";
            Laya.LocalStorage.setItem("Pencil-Rush-Online-musicState", JSON.stringify(Laya.SoundManager.muted));
        }
        onShowInt(e) {
            e.stopPropagation();
            platform.getInstance().showInterstitial();
            this.btn_showInt.visible = false;
        }
        onStartGame() {
            p.reportEvent("NewGame_StartClick"), p.reportEvent("GameStart"), o.getInstance().isDown = !0, e.Instance.gameNum++, 2 == e.Instance.gameNum ? p.reportEvent("NewGame_EnterNextGame2") : 3 == e.Instance.gameNum ? p.reportEvent("NewGame_EnterNextGame3") : 4 == e.Instance.gameNum ? p.reportEvent("NewGame_EnterNextGame4") : 5 == e.Instance.gameNum && p.reportEvent("NewGame_EnterNextGame5"), Laya.Scene.open(c.GameScene), this.playerSc.startGame = !0, N.Instance.isUpdatePicture = !1;
        }
        onOpenSkin() {
            Laya.Scene.open(c.SkinScene);
        }
        onOpenPicture() {
            Laya.Scene.open(c.PictureScene);
        }
        creatPlayer() {
            if (null == s.Instance.Player) {
                let e = new Laya.Sprite3D();
                s.Instance.currentLevelSp.addChild(e), this.playerSc = e.addComponent(I), s.Instance.Player = e;
            } else this.playerSc = s.Instance.Player.getComponent(I);
        }
        updateIntensify() {
            for (let t = 1; t <= 3; t++) switch (t) {
                case 1:
                    this.Intensify.getChildAt(t - 1).getChildAt(1).getChildAt(0).value = e.Instance.intensify.pencilNum.toString(), this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(1).getChildAt(1).value = e.Instance.intensify_PencilNum[e.Instance.intensify.pencilNum - 1][1].toString(), e.Instance.intensify.pencilNum < e.Instance.intensify_PencilNum.length ? (e.Instance.coinNum, e.Instance.intensify_PencilNum[e.Instance.intensify.pencilNum - 1][1]) : (this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(0).visible = !1, this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(1).visible = !1, this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(2).visible = !0);
                    break;
                case 2:
                    this.Intensify.getChildAt(t - 1).getChildAt(1).getChildAt(0).value = e.Instance.intensify.coinIntensify.toString(), this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(1).getChildAt(1).value = e.Instance.intensify_Coin[e.Instance.intensify.coinIntensify - 1][1].toString(), e.Instance.intensify.coinIntensify < e.Instance.intensify_Coin.length ? (e.Instance.coinNum, e.Instance.intensify_Coin[e.Instance.intensify.coinIntensify - 1][1]) : (this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(0).visible = !1, this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(1).visible = !1, this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(2).visible = !0);
                    break;
                case 3:
                    this.Intensify.getChildAt(t - 1).getChildAt(1).getChildAt(0).value = e.Instance.intensify.pencilLossIntensify.toString(), this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(1).getChildAt(1).value = e.Instance.intensify_PencilLoss[e.Instance.intensify.pencilLossIntensify - 1][1].toString(), e.Instance.intensify.pencilLossIntensify < e.Instance.intensify_PencilLoss.length ? (e.Instance.coinNum, e.Instance.intensify_PencilLoss[e.Instance.intensify.pencilLossIntensify - 1][1]) : (this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(0).visible = !1, this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(1).visible = !1, this.Intensify.getChildAt(t - 1).getChildAt(2).getChildAt(2).visible = !0);
            }
            this.tex_money.value = e.Instance.coinNum.toString(), A.saveData(v.intensify, e.Instance.intensify), A.saveData(v.coinNum, e.Instance.coinNum);
        }
        showTishi(e = "Coins Are Not Enough") {
            if (1 != this.tishi.visible) {
                this.tishi.visible = !0;
                var t = this;
                this.tishi.text = e, Laya.timer.once(500, this, function () {
                    t.tishi.visible = !1;
                });
            }
        }
    }
    class V {
        constructor() {
            this.gameName = "RocketSuperman", this.appid = "30420763", this.channel = "oppo_kyx_RocketSuperman", this.version = "1", this.packName = "com.lechang.RocketSuperman.kyx.nearme.gamecenter", this.openId = "123", this.recommendData = [], this.isOneMin = !1, this.xxNum = 0, this.bannerAd = null, this.videoAd = null, this.nativeAd = null, this.adId = null, this.nativeCurrentAdList = null, this.testUrl = [""], this.testID = 0, this.nativeIconAd = null, this.bannerJiange = 0, this.setting = {
                Lc_ADBannerJianGe: 0,
                Lc_JiesuanYuanshengBanner: 0,
                Lc_YuanshengBannerChakan: 0,
                Lc_GameStartOneMin: 0,
                Lc_ADClickType: 0,
                Lc_ADClickTouchType: 0,
                Lc_ADClickTouchTypeN: 0,
                Lc_isopenRecommend: 0
            };
        }
        static getInstance() {
            return null == this.instance && (this.instance = new V()), this.instance;
        }
        init() {
            console.log("初始化oppo广告插件");
            let e = this;
            this.getSetting(function () {
                let t = Math.floor(Date.now() / 864e5),
                    n = Laya.LocalStorage.getJSON("XXnum");
                n ? n.day != t ? e.xxNum = e.setting.Lc_ADClickTouchTypeN : e.xxNum = n.index : (e.xxNum = e.setting.Lc_ADClickTouchTypeN, Laya.LocalStorage.setJSON("XXnum", {
                    day: t,
                    index: e.xxNum
                })), console.log("误触次数", e.xxNum), 0 == e.setting.Lc_GameStartOneMin ? Laya.timer.once(6e4, this, function () {
                    e.isOneMin = !0;
                }) : e.isOneMin = !0;
            }), this.getRecommendFromSever(), Laya.Browser.onQGMiniGame && this.login();
        }
        login() {
            let e = this,
                t = Laya.Browser.window.qg.getLaunchOptionsSync();
            console.error(JSON.stringify(t)), console.log("start login"), Laya.Browser.window.qg.login({
                pkgName: e.packName,
                success: function (t) {
                    var n = JSON.stringify(t);
                    console.log(n), e.openId = t.uid, console.error("login success");
                },
                fail: function (e) {
                    console.error("login fail"), console.error(e);
                },
                complete: function () {
                    console.log("login complete");
                }
            });
        }
        creatAndShowBanner(e) {
            0 != this.isOneMin && (this.bannerAd && this.bannerAd.destroy(), this.bannerAd = qg.createBannerAd({
                adUnitId: e
            }), null != this.bannerAd && (this.bannerAd.show(), this.bannerAd.onShow(() => {
                console.log("banner创建展示成功");
            }), this.bannerAd.onError(e => {
                console.log("banner展示出错:", e);
            })));
        }
        hideBanner() {
            this.bannerAd && (console.log("隐藏banner"), this.bannerAd.hide());
        }
        showBanner() {
            this.bannerAd && (console.log("展示banner"), this.bannerAd.show());
        }
        showToast(e) {
            Laya.Browser.window.qg.showToast({
                title: e,
                icon: "none",
                duration: 2e3
            });
        }
        showVideo(e, t, n) {
            Laya.Browser.window.qg;
            var a = this;
            if (console.log("video adUnitId:", e), a.videoAd) {
                let e = a.videoAd.load();
                e && e.catch(e => {
                    console.error("=======================err.code========================" + JSON.stringify(e)), this.showToast("视频加载失败，请稍后再试");
                }), a.videoAd.offLoad(), a.videoAd.onLoad(() => {
                    a.videoAd.show();
                }), a.videoAd.offClose(), a.videoAd.onClose(e => {
                    e.isEnded ? t && "function" == typeof t && t() : n && "function" == typeof n && n();
                });
            } else a.videoAd = Laya.Browser.window.qg.createRewardedVideoAd({
                posId: e
            }), a.videoAd.load(), a.videoAd.onLoad(() => {
                let e = a.videoAd.show();
                e && e.catch(e => {
                    console.error("=======================err.code========================" + JSON.stringify(e)), this.showToast("视频加载失败，请稍后再试");
                });
            }), a.videoAd.onError(e => {
                console.error("=======================err.code1========================" + JSON.stringify(e)), this.showToast("视频加载失败，请稍后再试");
            }), a.videoAd.onClose(e => {
                e.isEnded ? t && "function" == typeof t && t() : n && "function" == typeof n && n();
            });
        }
        isDesktopExist(e) {
            let t = Laya.Browser.window.qg;
            t.getSystemInfoSync().platformVersionCode < 1044 || (t.hasShortcutInstalled ? t.hasShortcutInstalled({
                success: function (t) {
                    e && e(t);
                },
                fail: function (e) { },
                complete: function () { }
            }) : e(!1));
        }
        putDesktop(e) {
            let t = Laya.Browser.window.qg;
            t.getSystemInfoSync().platformVersionCode < 1040 || t.hasShortcutInstalled({
                success: function (n) {
                    0 == n && t.installShortcut({
                        success: function () {
                            e && e();
                        },
                        fail: function (e) {
                            console.log("install", JSON.stringify(e));
                        },
                        complete: function () { }
                    });
                },
                fail: function (e) {
                    console.log("isshotcut", e);
                },
                complete: function () { }
            });
        }
        preloadNativeAd(e, t = null) {
            let n, a, i = Laya.Browser.window.qg;
            if (i.getSystemInfoSync().platformVersionCode < 1051) return;
            let s = this;
            s.nativeAd && s.nativeAd.destroy(), n = i.createNativeAd({
                posId: e
            }), s.nativeAd = n, n.onLoad(function (e) {
                console.log("原生广告加载完成", JSON.stringify(e)), e && e.adList && (a = e.adList.pop(), console.log("nativeCurrentAdList", a), s.adId = a.adId, s.nativeCurrentAdList = a, null != t && t());
            }), n.onError(e => {
                switch (e.errCode) {
                    case -3:
                        console.error("原生广告加载失败---调用太频繁", JSON.stringify(e));
                        break;
                    default:
                        console.error("原生广告展示失败"), console.error(JSON.stringify(e));
                }
            }),
                function () {
                    let e = n.load();
                    e && e.then(() => { }).catch(e => {
                        console.error("原生加载失败", JSON.stringify(e));
                    });
                }();
        }
        showNativeAdByPreload(e, t, n, a, i) {
            var s = this;

            function reportAdClick() {
                s.nativeAd.reportAdClick({
                    adId: s.adId.toString()
                });
            }
            if (i) {
                let i = "";
                e.loadImage(i, Laya.Handler.create(this, function () {
                    e.parent.visible = !0, 1 == s.setting.Lc_ADClickType ? (e.on(Laya.Event.MOUSE_DOWN, this, function () {
                        console.log("点击原生");
                    }), t.on(Laya.Event.MOUSE_DOWN, this, function () {
                        a ? console.log("点击原生") : (console.log("点击跳过"), e.parent.visible = !1);
                    }), n.on(Laya.Event.MOUSE_DOWN, this, function () {
                        if (Math.random() < s.setting.Lc_ADClickTouchType && s.xxNum > 0) {
                            s.xxNum--;
                            let e = Math.floor(Date.now() / 864e5);
                            Laya.LocalStorage.setJSON("XXnum", {
                                day: e,
                                index: s.xxNum
                            }), console.log("点击误触原生");
                        }
                        e.parent.visible = !1;
                    })) : (e.on(Laya.Event.CLICK, this, function () {
                        console.log("点击原生");
                    }), t.on(Laya.Event.CLICK, this, function () {
                        a ? console.log("点击原生") : (console.log("点击跳过"), e.parent.visible = !1);
                    }), n.on(Laya.Event.CLICK, this, function () {
                        if (Math.random() < s.setting.Lc_ADClickTouchType && s.xxNum > 0) {
                            s.xxNum--;
                            let e = Math.floor(Date.now() / 864e5);
                            Laya.LocalStorage.setJSON("XXnum", {
                                day: e,
                                index: s.xxNum
                            }), console.log("点击误触原生");
                        }
                        e.parent.visible = !1;
                    }));
                }));
            } else if (this.nativeCurrentAdList && (s.nativeAd.reportAdShow({
                adId: s.adId.toString()
            }), console.log("原生banner"), e && t && (e.parent.visible = !1, s.nativeCurrentAdList.imgUrlList[0]))) {
                Laya.loader.load(s.nativeCurrentAdList.imgUrlList[0], Laya.Handler.create(this, function (i) {
                    i ? (console.log("res", typeof i), "string" == typeof i ? console.log("图片加载失败") : function () {
                        e.loadImage(s.nativeCurrentAdList.imgUrlList[0], Laya.Handler.create(this, function () {
                            console.log("加载图片完成"), s.hideBanner(), e.parent.visible = !0, e.offAll(Laya.Event.MOUSE_DOWN), t.offAll(Laya.Event.MOUSE_DOWN), n.offAll(Laya.Event.MOUSE_DOWN), e.on(Laya.Event.MOUSE_DOWN, this, function () {
                                e.parent.visible = !1, reportAdClick();
                            }), t.on(Laya.Event.MOUSE_DOWN, this, function () {
                                a && reportAdClick(), e.parent.visible = !1;
                            }), n.on(Laya.Event.MOUSE_DOWN, this, function () {
                                if (Math.random() < s.setting.Lc_ADClickTouchType && s.xxNum > 0) {
                                    reportAdClick(), s.xxNum--;
                                    let e = Math.floor(Date.now() / 864e5);
                                    Laya.LocalStorage.setJSON("XXnum", {
                                        day: e,
                                        index: s.xxNum
                                    });
                                }
                                e.parent.visible = !1;
                            });
                        }));
                    }()) : console.log("图片加载失败");
                }));
            }
        }
        showNativeIconAd(e, t, n, a) {
            if (0 == this.isOneMin) return;
            if (n) {
                let n = this;
                return void (e && (this.testID >= this.testUrl.length && (this.testID = 0), e.loadImage(this.testUrl[this.testID], Laya.Handler.create(this, function () {
                    e.parent.visible = !0;
                })), 1 == n.setting.Lc_ADClickType ? (e.offAll(Laya.Event.MOUSE_DOWN), e.on(Laya.Event.MOUSE_DOWN, this, function () {
                    console.log("点击原生广告", n.testID);
                }), t.offAll(Laya.Event.MOUSE_DOWN), t.on(Laya.Event.MOUSE_DOWN, this, function () {
                    if (Math.random() < n.setting.Lc_ADClickTouchType && n.xxNum > 0) {
                        n.xxNum--;
                        let e = Math.floor(Date.now() / 864e5);
                        Laya.LocalStorage.setJSON("XXnum", {
                            day: e,
                            index: n.xxNum
                        });
                    }
                    e.parent.visible = !1;
                })) : (e.offAll(Laya.Event.CLICK), e.on(Laya.Event.CLICK, this, function () {
                    console.log("点击原生广告", n.testID);
                }), t.offAll(Laya.Event.CLICK), t.on(Laya.Event.CLICK, this, function () {
                    if (Math.random() < n.setting.Lc_ADClickTouchType && n.xxNum > 0) {
                        n.xxNum--;
                        let e = Math.floor(Date.now() / 864e5);
                        Laya.LocalStorage.setJSON("XXnum", {
                            day: e,
                            index: n.xxNum
                        });
                    }
                    e.parent.visible = !1;
                })), this.testID++));
            }
            if (!Laya.Browser.onQGMiniGame) return;
            this.nativeIconAd && this.nativeIconAd.destroy(), this.nativeIconAd = qg.createNativeAd({
                adUnitId: a
            });
            let i = this.nativeIconAd,
                s = null;
            i.load(), i.onLoad(n => {
                console.log("原生icon加载", JSON.stringify(n));
                let a = n.adList.pop(),
                    o = a.icon;
                console.log("原生icon", o), s = a.adId, o && e && (i.reportAdShow({
                    adId: s
                }), e.loadImage(o, Laya.Handler.create(this, function () {
                    console.log("图片加载完成"), e.parent.visible = !0;
                })), e.offAll(Laya.Event.CLICK), e.on(Laya.Event.CLICK, this, function () {
                    i.reportAdClick({
                        adId: s
                    });
                }), t.offAll(Laya.Event.CLICK), t.on(Laya.Event.CLICK, this, function () {
                    e.parent.visible = !1;
                })), i.offLoad(function () { });
            }), i.onError(function (e) {
                console.log("原生icon加载失败", e), i.offError(function () { });
            });
        }
        showGamePortal(e) {
            let t = Laya.Browser.window.qg;
            if (t.getSystemInfoSync().platformVersionCode < 1076) console.log("快应用平台版本号低于1076，暂不支持互推盒子相关 API");
            else {
                var n, a = this;
                (n = t.createGamePortalAd({
                    adUnitId: e
                })).onLoad(function () {
                    console.log("互推盒子九宫格广告加载成功"), n.show().then(function () {
                        a.hideBanner(), console.log("show success");
                    }).catch(function (e) {
                        console.log("show fail with:" + e.errCode + "," + e.errMsg);
                    }), n.offLoad(null);
                }), n.onError(function (e) {
                    console.log("盒子九宫格广告加载失败", JSON.stringify(e));
                }), n.onClose(function () {
                    console.log("互推盒子九宫格广告关闭"), a.showBanner();
                }), n.load().then(function () {
                    console.log("load success");
                }).catch(function (e) {
                    console.log("load fail with:" + e.errCode + "," + e.errMsg);
                });
            }
        }
        getRecommendFromSever() {
            let e = "";
            e += this.appid + "&channel=" + this.channel, u.get(e, this, e => {
                try {
                    e.data && (this.recommendData = e.data, console.log("互推数据", this.recommendData));
                } catch (e) { }
            });
        }
        getSetting(e) {
            var t = this,
                n = "" + this.appid + "&channel=" + this.channel + "&AB_action=" + this.version;
            console.log("getSetting", n), u.get(n, this, function (n) {
                if (console.log(n), 200 == n.state) {
                    let a = n.data;
                    a && a.setting && (t.setting = a.setting, console.log("设置开关", t.setting), console.log(JSON.stringify(t.setting)), e && e());
                }
            });
        }
    }
    V.instance = null;
    class O extends Laya.Script {
        constructor() {
            super(...arguments), this.adUnitId = null, this.btnID = 0, this.isHuxi = !1, this.scaleX = 1, this.scaleY = 1, this.newScaleX = .8, this.newScaleY = .8, this.maxScaleX = 1.2, this.maxScaleY = 1.2, this.speed = .6, this.timer = .8, this.t = .8;
        }
        onStart() {
            this.gameObject = this.owner, this.scaleX = this.owner.scaleX, this.scaleY = this.owner.scaleX, this.newScaleX = .8 * this.scaleX, this.newScaleY = .8 * this.scaleY, this.maxScaleX = 1.2 * this.scaleX, this.maxScaleY = 1.2 * this.scaleY;
        }
        onClick(e) {
            let t = this;
            this.scene.onVideo(this.btnID, function (e, n = !0, a = null) {
                if (0 == n) return console.log("不看视频"), void e();
                L.getInstance().stopBGM()
                platform.getInstance().showReward(() => {
                    if(Laya.SoundManager.muted == false)
                        L.getInstance().recoverBGM()
                    e && e();
                }, () => {
                    if(Laya.SoundManager.muted == false)
                        L.getInstance().recoverBGM()
                    a && a();
                })
            });
        }
        onUpdate() {
            this.isHuxi && (this.t -= .001 * Laya.timer.delta, this.t < 0 && (this.speed = -this.speed, this.t = this.timer), this.scaleX += .001 * Laya.timer.delta * this.speed, this.scaleY += .001 * Laya.timer.delta * this.speed, this.scaleY < this.newScaleY ? (this.scaleY = this.newScaleY, this.t = 0) : this.scaleY > this.maxScaleY && (this.scaleY = this.maxScaleY, this.t = 0), this.scaleX < this.newScaleX ? (this.scaleX = this.newScaleX, this.t = 0) : this.scaleX > this.maxScaleX && (this.scaleX = this.maxScaleX, this.t = 0), this.gameObject.scale(this.scaleX, this.scaleY, !0));
        }
    }
    class R extends S.Views.OpenPencilBoxSceneUI {
        constructor() {
            super(...arguments), this.isMove = !1, this.y1 = .25, this.t = 1;
        }
        onVideo(e, t) {
            let n = this;
            t(function () {
                n.playerSc.onOpenPencilBox(), n.playerSc.isFinish = !1, s.Instance.current_pencil_case.active = !1, n.close(), P.instance && (P.instance.visible = !0), n.playerSc.isHaveOpenBox = !0, N.Instance.isUpdatePicture = !1;
            }, !0, function () {
                p.reportEvent("NewGame_MoBoxCancel"), p.reportEvent("GameMoBoxCancel");
            }), p.reportEvent("NewGame_MoBoxVideo"), p.reportEvent("GameMoBoxVideo");
        }
        onAwake() {
            let e = this;
            this.height = Laya.stage.height, this.case_pos = s.Instance.current_pencil_case.transform.position.clone();
            let t = s.Instance.current_pencil_case.parent.getChildAt(0).transform.position;
            t.setValue(s.Instance.Player.transform.position.x, t.y, s.Instance.Player.transform.position.z - 2.5), this.btn_exit.once(Laya.Event.CLICK, this, this.onExit), i.AnimationTool.moveTo3d(s.Instance.current_pencil_case, t, 1e3, !1, Laya.Handler.create(this, function () {
                e.isMove = !0, L.getInstance().playSound("pencil_box");
            })), this.playerSc = s.Instance.Player.getComponent(I), Laya.timer.frameLoop(1, this, this.onUpdate), m.getInstance().hideBanner(), p.reportEvent("GameMoBoxShow");
        }
        onExit() {
            Laya.Scene.open(c.WinScene);
        }
        onDisable() {
            let e = this;
            i.AnimationTool.moveTo3d(s.Instance.current_pencil_case, this.case_pos, 1e3, !1, Laya.Handler.create(this, function () {
                e.isMove = !1, s.Instance.current_pencil_case.transform.rotationEuler = new Laya.Vector3(0, 180, 0);
            })), Laya.timer.clearAll(this), p.reportEvent("NewGame_MoBoxOver");
        }
        onUpdate() {
            this.isMove && (s.Instance.current_pencil_case.transform.rotate(new Laya.Vector3(0, .001 * Laya.timer.delta * 3, 0)), this.t -= .001 * Laya.timer.delta, this.t < 0 && (this.y1 = -this.y1, this.t = 1), s.Instance.current_pencil_case.transform.translate(new Laya.Vector3(0, this.y1 * Laya.timer.delta * .001, 0)));
        }
    }
    class B extends i.Script3D {
        constructor() {
            super(...arguments), this.myID = 0, this.isDa = !0, this.isMoving = !1;
        }
        onAwake() {
            super.onAwake();
        }
        init(t, n, a) {
            this.camera = t, this.targetPos = new Laya.Vector3(this.transform.position.x, this.transform.position.y, this.transform.position.z + 12), this.myID = n, this.scene = a, this.cameraPos = this.camera.transform.position.clone(), this.myID + 1 == e.Instance.album.haved[e.Instance.album.haved.length - 1] && e.Instance.isHaveNewPicture && this.ani();
        }
        onMouseClick() {
            if (this.myID + 1 == e.Instance.album.haved[e.Instance.album.haved.length - 1] && e.Instance.isHaveNewPicture) return e.Instance.isHaveNewPicture = !1, void this.playParticle();
            if (this.isMoving || e.Instance.isHaveNewPicture) return;
            let t = this;
            this.isMoving = !0, this.isDa ? (this.cameraPos = this.camera.transform.position.clone(), i.AnimationTool.moveTo3d(this.camera, this.targetPos, 1e3, !1, Laya.Handler.create(this, function () {
                t.isDa = !1, t.isMoving = !1;
            }))) : i.AnimationTool.moveTo3d(this.camera, this.cameraPos, 1e3, !1, Laya.Handler.create(this, function () {
                t.isDa = !0, t.isMoving = !1;
            }));
        }
        ani() {
            if (this.isMoving) return;
            let e = this;
            this.isMoving = !0, this.isDa ? (this.cameraPos = this.camera.transform.position.clone(), i.AnimationTool.moveTo3d(this.camera, this.targetPos, 1e3, !1, Laya.Handler.create(this, function () {
                e.isDa = !1, e.isMoving = !1;
            }))) : i.AnimationTool.moveTo3d(this.camera, this.cameraPos, 1e3, !1, Laya.Handler.create(this, function () {
                e.isDa = !0, e.isMoving = !1;
            }));
        }
        onStart() {
            let t = this.gameObject.getChildAt(0).getChildAt(0).getChildAt(0),
                n = this.gameObject.getChildAt(0).getChildAt(0).getChildAt(1);
            if (-1 != e.Instance.album.haved.indexOf(this.myID + 1)) {
                if (this.myID + 1 == e.Instance.album.haved[e.Instance.album.haved.length - 1] && e.Instance.isHaveNewPicture) {
                    let e = new Laya.Vector4();
                    return this.camera.viewport.project(this.transform.position, this.camera.projectionViewMatrix, e), this.camera.worldToViewportPoint(this.transform.position, e), console.log(e), void (e.w > 0 && (this.scene.hand.visible = !0, this.scene.hand.pos(e.x / Laya.stage.clientScaleX, e.y / Laya.stage.clientScaleY)));
                }
                t.active = !1;
                let a = n.meshRenderer.materials[1],
                    i = "UI/texture/" + e.Instance.texture[this.myID + 1];
                console.log(i), Laya.Texture2D.load(i, Laya.Handler.create(this, function (e) {
                    a.albedoTexture = e;
                }));
            } else t.active = !0;
        }
        playParticle() {
            console.log("播放粒子"), this.scene.hand.visible = !1;
            let t = this.gameObject.getChildAt(0).getChildAt(0).getChildAt(0),
                n = this.gameObject.getChildAt(0).getChildAt(0).getChildAt(1);
            Laya.Sprite3D.instantiate(s.Instance.particleRoot.getChildByName("Hua"), s.Instance.currentLevelSp).transform.position = new Laya.Vector3(this.transform.position.x, this.transform.position.y, this.transform.position.z + 5);
            let a = this;
            Laya.timer.once(1e3, this, function () {
                t.active = !1;
                let i = n.meshRenderer.materials[1],
                    s = "UI/texture/" + e.Instance.texture[a.myID + 1];
                Laya.Texture2D.load(s, Laya.Handler.create(a, function (e) {
                    i.albedoTexture = e;
                })), a.scene.showBtn(), a.ani();
            });
        }
    }
    class k extends S.Views.PictureSceneUI {
        constructor() {
            super(...arguments), this.roomPoints = [], this.dirPos = new Laya.Vector3(), this.ro = new Laya.Vector3(), this.isClose = !1, this.isMoving = !1, this.currentRoom = 1;
        }
        onAwake() {
            if (this.height = Laya.stage.height, this.btn_exit.on(Laya.Event.CLICK, this, this.onExit), this.btn_goon.on(Laya.Event.CLICK, this, this.onExit), this.btn_right.on(Laya.Event.CLICK, this, this.onRight), this.btn_left.on(Laya.Event.CLICK, this, this.onLeft), e.Instance.isHaveNewPicture && e.Instance.album.haved.length <= 16) {
                let t = e.Instance.album.haved[e.Instance.album.haved.length - 1];
                p.reportEvent("GameMyPictureNum_" + t);
                let n = Math.floor(t / 4.5);
                n > 3 && (n = 3), this.currentRoom = n + 1, console.log("房间号", this.currentRoom), this.btn_exit.visible = !1, this.btn_goon.visible = !1, this.lr.visible = !1;
            }
            this.init(), this.updateLRbtn(), p.reportEvent("GameEnterMyPicture");
        }
        init() {
            this.dirPos = s.Instance.directionalLight.transform.position.clone(), this.ro = s.Instance.directionalLight.transform.rotationEuler.clone(), this.height = Laya.stage.height;
            let e = Laya.Sprite3D.instantiate(s.Instance.pre_painting, s.Instance.Scene3D, !1, new Laya.Vector3(1e3, 1e3, 1e3));
            this.camera = e.getChildAt(0).getChildAt(0).getChildByName("MainCamera"), this.light = e.getChildAt(0).getChildAt(0).getChildByName("Directional Light"), this.light.active = !1, s.Instance.directionalLight.transform.position = this.light.transform.position, s.Instance.directionalLight.transform.rotationEuler = this.light.transform.rotationEuler, this.camera.fieldOfView = 50;
            let t = 0;
            for (let n = 0; n < 4; n++) {
                let a = e.getChildAt(0).getChildAt(0).getChildAt(n).getChildAt(0).transform.position;
                this.roomPoints.push(a);
                for (let a = 0; a < 4; a++) {
                    e.getChildAt(0).getChildAt(1).getChildAt(n).getChildByName("Pictures").getChildAt(a).addComponent(B);
                }
            }
            this.camera.transform.position = this.roomPoints[this.currentRoom - 1], this.sp3d = e;
            for (let n = 0; n < 4; n++) {
                for (let a = 0; a < 4; a++) {
                    e.getChildAt(0).getChildAt(1).getChildAt(n).getChildByName("Pictures").getChildAt(a).getComponent(B).init(this.camera, t, this), t++;
                }
            }
            s.Instance.Camera.active = !1;
        }
        onExit() {
            this.isClose ? (this.close(), this.view.visible = !0) : Laya.Scene.open(c.LobbyScene), this.sp3d.destroy(!0), s.Instance.Camera.active = !0, s.Instance.directionalLight.transform.position = this.dirPos, s.Instance.directionalLight.transform.rotationEuler = this.ro, p.reportEvent("GameEnterMyPictureContinue");
        }
        onOpened(e) {
            e && e[0] == c.WinScene && (this.isClose = !0, this.view = e[1]);
        }
        onDisable() {
            Laya.timer.clearAll(this);
        }
        onRight() {
            if (this.isMoving || this.currentRoom > 3) return;
            let e = this;
            this.isMoving = !0, i.AnimationTool.moveTo3d(this.camera, this.roomPoints[this.currentRoom], 400, !1, Laya.Handler.create(this, function () {
                e.isMoving = !1;
            })), e.currentRoom++, this.updateLRbtn(), p.reportEvent("GameEnterMyPictureCheck");
        }
        onLeft() {
            if (this.isMoving || this.currentRoom <= 1) return;
            let e = this;
            this.isMoving = !0, i.AnimationTool.moveTo3d(this.camera, this.roomPoints[this.currentRoom - 2], 400, !1, Laya.Handler.create(this, function () {
                e.isMoving = !1;
            })), e.currentRoom--, this.updateLRbtn(), p.reportEvent("GameEnterMyPictureCheck");
        }
        updateLRbtn() {
            this.currentRoom <= 1 ? this.btn_left.visible = !1 : this.btn_left.visible = !0, this.currentRoom >= 4 ? this.btn_right.visible = !1 : this.btn_right.visible = !0;
        }
        showBtn() {
            this.btn_exit.visible = !0, this.btn_goon.visible = !0, this.lr.visible = !0;
        }
    }
    class U extends Laya.Script {
        constructor() {
            super(...arguments), this.scaleX = 1, this.scaleY = 1, this.newScaleX = .8, this.newScaleY = .8, this.maxScaleX = 1.2, this.maxScaleY = 1.2, this.speed = .6, this.timer = .8, this.t = .8;
        }
        onStart() {
            this.gameObject = this.owner, this.scaleX = this.owner.scaleX, this.scaleY = this.owner.scaleX, this.newScaleX = .8 * this.scaleX, this.newScaleY = .8 * this.scaleY, this.maxScaleX = 1.2 * this.scaleX, this.maxScaleY = 1.2 * this.scaleY;
        }
        onUpdate() {
            this.t -= .001 * Laya.timer.delta, this.t < 0 && (this.speed = -this.speed, this.t = this.timer), this.scaleX += .001 * Laya.timer.delta * this.speed, this.scaleY += .001 * Laya.timer.delta * this.speed, this.scaleY < this.newScaleY ? (this.scaleY = this.newScaleY, this.t = 0) : this.scaleY > this.maxScaleY && (this.scaleY = this.maxScaleY, this.t = 0), this.scaleX < this.newScaleX ? (this.scaleX = this.newScaleX, this.t = 0) : this.scaleX > this.maxScaleX && (this.scaleX = this.maxScaleX, this.t = 0), this.gameObject.scale(this.scaleX, this.scaleY, !0);
        }
    }
    class G extends S.Views.SkinSceneUI { }
    class z extends S.Views.SpecialSkinSceneUI {
        constructor() {
            super(...arguments), this.skinID = 1;
        }
        onVideo(t, n) {
            let a = this;
            n(function () {
                e.Instance.Skin.mySkin = a.skinID, Laya.Scene.open(c.LobbyScene), N.Instance.updateSkin();
            }, !0, function () {
                p.reportEvent("GamePenShiwanCancel");
            }), p.reportEvent("GamePenShiwanVideo");
        }
        onAwake() {
            this.height = Laya.stage.height, this.bg.height = this.height, this.tex_money.value = e.Instance.coinNum.toString(), this.btn_exit.on(Laya.Event.CLICK, this, this.onExit);
            let t = [];
            for (let e = 1; e < 9; e++) t.push(e);
            let n = i.MathTool.getRandomInt(t.length);
            this.skinID = t[n], this.sp_big.loadImage("UI/skinTexture/" + this.skinID + ".png");
        }
        onExit() {
            Laya.Scene.open(c.LobbyScene), N.Instance.updateSkin();
        }
    }
    class H extends S.Views.WinSceneUI {
        constructor() {
            super(...arguments), this.isClick = !1, this.nextLevel = null;
        }
        onVideo(t, n) {
            if (this.isClick) return;
            if (null == this.nextLevel) return;
            let a = this;
            this.isClick = !0;
            n(function () {
                let t = e.Instance.album.haved.length / 4;
                b.CoinAni(3 * e.Instance.winCoinNum, a.tex_money, a, Laya.Handler.create(this, function () {
                    a.nextLevel && (N.Instance.loadLevelByPreload(a.nextLevel), e.Instance.isHaveNewPicture && e.Instance.album.haved.length <= 16 ? Laya.Scene.open(c.PictureScene) : Laya.Scene.open(c.LobbyScene));
                }));
            }, !0, function () {
                e.Instance.coinNum += e.Instance.winCoinNum, a.nextLevel && (N.Instance.loadLevelByPreload(a.nextLevel), e.Instance.isHaveNewPicture && e.Instance.album.haved.length <= 16 ? Laya.Scene.open(c.PictureScene) : Laya.Scene.open(c.LobbyScene));
            }), p.reportEvent("NewGame_GameOverReward3"), p.reportEvent("GameOver_ADclick");
        }
        onAwake() {
            let t = this;
            this.height = Laya.stage.height, this.fon_wincoin.value = e.Instance.winCoinNum.toString(), this.tex_money.value = e.Instance.coinNum.toString(), this.tex_winCoin.text = e.Instance.winCoinNum.toString(), this.tex_level.text = e.Instance.currentLevel.toString(), p.reportEvent("GameLevelover_" + e.Instance.currentLevel.toString()), p.AldStageOnEnd({
                stageId: e.Instance.currentLevel.toFixed(0),
                stageName: e.Instance.currentLevel.toFixed(0),
                event: "complete"
            }), e.Instance.currentLevel++, A.saveData(v.newUser, "false"), N.Instance.preloadLevel(Laya.Handler.create(this, function (e) {
                t.nextLevel = e, t.btn_exit.once(Laya.Event.CLICK, t, t.onExit);
            })), A.saveData(v.pictureData, e.Instance.PictureData), A.saveData(v.album, e.Instance.album), A.saveData(v.level, e.Instance.currentLevel), this.btn_picture.on(Laya.Event.CLICK, this, this.onOpenPicture), e.Instance.Skin.mySkin = -1, p.reportEvent("NewGame_GameOver"), p.reportEvent("GameOverok"), p.reportEvent("GameOver");
        }
        onExit() {
            let t = this;
            if (this.isClick) return;
            this.isClick = !0;
            b.CoinAni(e.Instance.winCoinNum, this.tex_money, this, Laya.Handler.create(this, function () {
                t.nextLevel && (N.Instance.loadLevelByPreload(t.nextLevel), e.Instance.isHaveNewPicture && e.Instance.album.haved.length <= 16 ? Laya.Scene.open(c.PictureScene) : Laya.Scene.open(c.LobbyScene));
            })), p.reportEvent("NewGame_GameOverReward1"), p.reportEvent("GameOver_click");
        }
        onOpenPicture() {
            this.visible = !1, Laya.Scene.open(c.PictureScene, !1, [c.WinScene, this]);
        }
    }
    class X {
        constructor() { }
        static init() {
            var e = Laya.ClassUtils.regClass;
            e("Scripts/View/FailScene.ts", E), e("Scripts/tool/Btn.ts", D), e("Scripts/View/GameScene.ts", P), e("Scripts/tool/Prefabs.ts", _), e("Scripts/View/LoadingScene.ts", T), e("Scripts/View/LobbyScene.ts", M), e("Plugin/LcAD/VideoAD.ts", O), e("Scripts/View/OpenPencilBoxScene.ts", R), e("Scripts/View/PictureScene.ts", k), e("Scripts/tool/BtnAni.ts", U), e("Scripts/View/SkinScene.ts", G), e("Scripts/View/SpecialSkinScene.ts", z), e("Scripts/View/WinScene.ts", H);
        }
    }
    X.width = 750, X.height = 1334, X.scaleMode = "showall", X.screenMode = "none", X.alignV = "middle", X.alignH = "center", X.startScene = "Views/LoadingScene.scene", X.sceneRoot = "", X.debug = !1, X.stat = !1, X.physicsDebug = !1, X.exportSceneToJson = !0, X.init();
    class F {
        constructor() {
            this.simpleShaderVS = '\n    #if defined(GL_FRAGMENT_PRECISION_HIGH)//\n\tprecision highp float;\n#else\n\tprecision mediump float;\n#endif\n\n\n#include "Lighting.glsl";\nattribute vec4 a_Position;\nattribute vec2 a_Texcoord0;\n\n#ifdef GPU_INSTANCE\n\tattribute mat4 a_MvpMatrix;\n#else\n\tuniform mat4 u_MvpMatrix;\n#endif\n\nvarying vec2 v_Texcoord0;\n\nvoid main()\n{\n    #ifdef GPU_INSTANCE\n\t\tgl_Position = a_MvpMatrix * a_Position;\n\t#else\n\t\tgl_Position = u_MvpMatrix * a_Position;\n\t#endif\n\n\tv_Texcoord0=a_Texcoord0;\n\n    gl_Position=remapGLPositionZ(gl_Position);\n}\n', this.simpleShaderFS = "\n    #if defined(GL_FRAGMENT_PRECISION_HIGH)//\n\tprecision highp float;\n#else\n\tprecision mediump float;\n#endif\n\nuniform sampler2D u_AlbedoTexture;\nuniform sampler2D u_MaskTexture;\nuniform float u_maskValue;\nvarying vec2 v_Texcoord0;\n\nvoid main()\n{    \n    vec4 _color = texture2D(u_AlbedoTexture, v_Texcoord0);\n    vec4 _maskColor=texture2D(u_MaskTexture,v_Texcoord0);\n    if(_color.r<=0.0){\n        _color.rgb=vec3(1.0,1.0,1.0);\n    }\n    if(_maskColor.r<u_maskValue){\n        _color.rgb=vec3(1.0,1.0,1.0);\n    }\n    gl_FragColor=_color;\n}\n";
        }
        static get Instance() {
            return null == this._instance && (this._instance = new F()), this._instance;
        }
        initShader() {
            var e = {
                a_Position: Laya.VertexMesh.MESH_POSITION0,
                a_MvpMatrix: Laya.VertexMesh.MESH_MVPMATRIX_ROW0,
                a_Texcoord0: Laya.VertexMesh.MESH_TEXTURECOORDINATE0
            },
                t = {
                    u_MvpMatrix: Laya.Shader3D.PERIOD_SPRITE,
                    u_AlbedoTexture: Laya.Shader3D.PERIOD_MATERIAL,
                    u_MaskTexture: Laya.Shader3D.PERIOD_MATERIAL,
                    u_maskValue: Laya.Shader3D.PERIOD_MATERIAL
                },
                n = Laya.Shader3D.add("MaskShader"),
                a = new Laya.SubShader(e, t);
            n.addSubShader(a), a.addShaderPass(this.simpleShaderVS, this.simpleShaderFS);
        }
    }
    F._instance = null;
    new class {
        constructor() {
            window.Laya3D ? Laya3D.init(X.width, X.height) : Laya.init(X.width, X.height, Laya.WebGL), Laya.stage.scaleMode = X.scaleMode, Laya.stage.screenMode = X.screenMode, Laya.stage.alignV = X.alignV, Laya.stage.alignH = X.alignH, Laya.URL.exportSceneToJson = X.exportSceneToJson;
            window.yad = platform.getInstance().createLogo();
            window.yad.top = 0;
            window.yad.right = 0;
            Laya.ResourceVersion.enable("version.json", Laya.Handler.create(this, this.onVersionLoaded), Laya.ResourceVersion.FILENAME_VERSION);
        }
        onVersionLoaded() {
            Laya.AtlasInfoManager.enable("fileconfig.json", Laya.Handler.create(this, this.onConfigLoaded));
        }
        startMiniGameSDK() {
            // @ts-ignore
            if (typeof minigame !== 'undefined') {
                //@ts-ignore
                minigame.setLoadingProgress(100);
                //@ts-ignore
                minigame.startGameAsync()
                    .then(function () {
                        //加载IDE指定的场景，这里假定第一个场景名称是startScene
                        F.Instance.initShader(), X.startScene && Laya.Scene.open(X.startScene);
                    })
                    .catch(function (e) {
                        console.info("startGameAsync error: " + e);
                    });
            }


        }
        onConfigLoaded() {
            minigame.initializeAsync()
                .then(()=>{
                    console.log("FB initializeAsync");
                    this.startMiniGameSDK();
                });
        }
    }();
}();