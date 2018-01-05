# Awesome NCL

[Nested Context Language (NCL)](http://www.ncl.org.br) is an XML-based
declarative language to support the development of interactive multimedia
presentations.  It is an [ISDB-T](http://en.wikipedia.org/wiki/SBTVD)
international standard for Terrestrial Digital TV, and an [ITU-T
recommendation](http://www.itu.int/rec/T-REC-H.761) for IPTV services.

This page is a curated lists of resources supporting NCL.


## Applications, Players, and Plugins for NCL viewing

### Open source players

  * [Ginga-NCL Reference Implementation](http://github.com/telemidia/ginga) is
    the ITU-T reference NCL player mainly developed by
    [TeleMídia Lab/PUC-Rio](http://www.telemidia.puc-rio.br).
  * [Ginga.ar](http://tvd.lifia.info.unlp.edu.ar/ginga.ar/index.php/download) is
    a fork of Ginga-NCL Reference Implementation being developed by the
    Argentine Community.
  * [GHTV NCL Player](https://github.com/expertisesolutions/ghtv-ncl-player)
    by [Expertise Solutions](http://www.expertisesolutions.com.br).
  * [WebNCL](https://github.com/lince/webncl.git) is a lightweight NCL
    presentation machine based on the Web technologies stack
    (HTML5/JavaScript/CSS).  By using WebNCL, NCL documents can be presented
    in any device that has an HTML5 compatible browser, such as tablets,
    smartphones, smart TVs and PCs.
  * [pywebncl](https://github.com/caioviel/pywebncl) is a Python wrapper for
    WebNCL which allows local reprodution of NCL documents.
  * [NCL4Web](http://www.midiacom.uff.br/~caleb/ncl4web) is a tool for
    presenting NCL documents in web browsers. It translates an NCL 3.0
    multimedia document into an HTM5 + JavaScript document using a XSLT
    Stylesheet.
  * [NCLua](https://github.com/gflima/nclua) library.

### Commercial players

  * [Mopa Embedded Systems](http://www.linkedin.com/company/mopa-embedded-systems)
  * [AstroDevNet](https://www.astrodevnet.com.br/AstroDevNet/home.html)

Some developers trying to easy the use of the system as a whole have created
Virtual Machines with everything you need already configured.  It is the case
of:

  * [Ginga-NCL Virtual Set-top Box](http://www.gingancl.org.br/sites/gingancl.org.br/files/ferramentas/ubuntu-server10.10-ginga-v.0.12.4-i386.zip|Ginga-NCL)
    is a Linux-based VMWare image with including Ginga-NCL. (It looks outdated!)
  * [GingaAIO](http://www.telemidia.puc-rio.br/~edcaraujo/gingaaio) is a
    virtual machine for execution and authoring of NCL application. Unlike
    Ginga-NCL Vittual Set-top Box, gingaaio also includes a graphical
    environment to easy the creation and execution of NCL applications. (It
    looks outdated!)

### Others
  * [Ginga CDN](http://gingacdn.lavid.ufpb.br)
  * [ffginga](http://code.google.com/p/ffginga) is a standard compliant free
    software implementation of the SBTVD middleware (Ginga-NCL and Ginga-J).
    (It looks outdated!).
  * [GingaBuild](http://code.google.com/p/gingabuild) is a shell script
    program to install and configure a a Ginga development environment. (It
    looks outdated!)


## Authoring support

### Authoring tools

  * [NCL Composer](http://composer.telemidia.puc-rio.br) is an extensible
    authoring tool to support mixed (textual and visual) authoring of NCL
    applications.
  * [NCL Eclipse](http://www.telemidia.puc-rio.br/~roberto/ncleclipse) is an
    Eclipse plugin aware of NCL syntax and elements relations.
  * [ISB Designer](http://www.telemidia.puc-rio.br/~edcaraujo/isbdesigner) is
    an authoring tool with the aim of supporting interactive storyboards. The
    tool can export NCL documents.
  * [Cacuriá](http://www.telemidia.puc-rio.br/tools/cacuria.html) is an
    authoring tool suporting the creating of hypervideo-based learning
    objects, and that can export to NCL.
  * [NCL/Lua plug-in for Gedit](http://wiki.ginga.org.ar/doku.php?id=herramientas:plugin_gedit)
  * [NCL/Lua plug-in for Latex](http://wiki.ginga.org.ar/doku.php?id=herramientas:plugin_latex)
  * [Berimbau iTV Author](http://www.batuque.tv/|Berimbau iTV Author) was
    created focused on designers and media professionals, allowing them to
    create interactive applications without programming knowledge. The tool is
    free to use (but it is not open-source).
  * [Celula](http://www.youtube.com/watch?v=nRQUDaKiIsk) is an authoring tool
    developed by INCoD focused on creating interactive content for digital TV.
  * [CreaTVDigital](http://code.google.com/p/creatvdigital|CreaTVDigital) is a
    tool aiming at easing the development of interactive Digital TV
    application by media professionals. It follows a WYSIWYG approach and does
    not require authors to know NCL or Lua.
  * [Iris (Cpqd)](http://www.cpqd.com.br/component/content/article/346-resultados-disponiveis/6150-ferramenta-de-autoria.html)
    is a graphical tool that allows for content producer to create interactive
    multimedia application without the necessity of coding.
  * [Creative-NCL](http://laws.deinf.ufma.br/creative-ncl) is a web-based tool
    that allows for the creation of NCL documents through visual abstractions.
  * [Guri Project](http://guri.upf.br) __FIXME__.
  * [NEXT](http://www2.ic.uff.br/PosGraduacao/Dissertacoes/553.pdf) is an
    authoring tool for NCL documents using templates.  It is based on plugins,
    where each plugin provides a different view of the document (spatial,
    textual and structural) or a facility for creating document parts
    (connector plugin).  NEXT allows the author to choose a template from a
    template base and fill it, through a set of screens, in order to create an
    NCL document (available at request).
  * [STEVE](http://www.midiacom.uff.br) is an authoring tool designed based on
    commercial tools for creating multimedia presentations.  It allows the
    author to create an NCL document from its temporal view. STEVE allows
    creating temporal relations among media objects, including interaction
    relations.
  * [Ginga Studio](http://repositorio.espe.edu.ec/handle/21000/13468)
    __FIXME__.

### Validation tools

  * [NCL Validator --- Java](http://github.com/ncleclipse/ncl30-validator) is a
    Java-based validator for NCL documents.  It is currently integrated into
    [NCL Eclipse](http://www.telemidia.puc-rio.br/~roberto/ncleclipse) and
    [nclvs](http://validator.ncl.org.br).
  * [NCL Validator --- C](http://sourceforge.net/projects/ncl-validator/) is a
    C-based software for incremental validation of NCL documents.  Currently,
    its source code is integrated into
    [NCL Composer](http://composer.telemidia.puc-rio.br).
  * [nclvs (NCL Validator Service)(http://validator.ncl.org.br) is an online
    validation service for NCL documents.
  * [ncl-inspector](http://code.google.com/p/ncl-inspector) is a rule-based
    critique system to evaluate NCL applications code quality automatically.
  * [aNaa4Web](http://www.midiacom.uff.br/~joel/anaa4web) is an interface built
    upon the aNaa API.
  * [Property Editor](http://www.midiacom.uff.br) is an editor for creating
    temporal properties to be validated in an NCL document and performing the
    validation.

### Template-based authoring

  * [LuaTPL](https://github.com/robertogerson/luatpl) enables
    [Lua](http://lua.org) to be used as a template specification language in a
    similar way to how PHP, ASP, JSP, etc. are integrated to HTML.  In special,
    the use of Lua as base for template specification in the scope of Ginga-NCL
    also allows for processing this templates in the client side, since Lua is a
    standard for developing iDTV applications for Ginga-NCL.
  * [TAL (Template Authoring Language)](http://www.telemidia.puc-rio.br/tools/)
    is an authoring language for hypermedia document templates.
  * [XTemplate](http://joel.dossantos.cc/XTemplate.html) 3.0 is a language to
    create composite templates for NCL. The composite templates describe, in a
    generic way, the behavior of an NCL context.
  * [EDITEC](http://www.midiacom.uff.br) is an authoring tool for XTemplate 3.0
    templates.
  * [LUAR](http://www.natalnet.br/luar) is a framework for agile development of
    applications written in NCL/NCLua for Digital TV.
  * [NCLForms](http://www.midiacom.uff.br/midiacom/index.php/pt-BR/downloads/ferramentas/149-nclforms)
    aims at providing NCL developers with a set of graphical interface widgets
    to easy the integration of forms into Digital TV applications.

### Libraries and frameworks

  * [ATHUS.ar](http://www.pladema.net/tvdigital/?page_id=6) __FIXME__.
  * [WLL4TV ((Widgets Lua Library for TV)](http://www.pladema.net/tvdigital/?page_id=6) __FIXME__.
  * [LuaonTV](http://luaforge.net/projects/luaontv) __FIXME__.
  * [NCLuaHTTP](https://github.com/manoelcampos/NCLuaHTTP) is an NCLua module
    that implements the HTTP 1.0/1.1 protocol.
  * [NCLuaSOAP](https://github.com/manoelcampos/NCLuaSOAP) is an NCLua module
    that implements the SOAP 1.1/1.2 protocol.
  * [aNa (API for NCL authoring)](https://github.com/joeldossantos/aNa) is an
    API for representing NCL documents through Java classes.  Its purpose is to
    help programmers to create tools that manipulate NCL code.
  * [aNaa (API for NCL authoring and analysis)](http://www.midiacom.uff.br/~joel/anaa4web/)
    is an extension of aNa providing methods for performing document validation.
  * [NCLuaRSS-Reader](https://github.com/manoelcampos/NCLuaRSS-Reader) is an RSS
    feed reader for Digital TV.

### Alternative syntaxes

  * [JNS (JSON NCL Script)](http://www.midiacom.uff.br/~caleb/documentacaoJNS/)
    is an alternative syntax to write NCL documents.  Instead of XML, JNS uses
    JSON.  Additionally, JNS includes new features aiming at to improve reuse
    and easy programming.  For instance, JNS allows inline declaration of
    descriptors, rules and regions in the document's body. (If you do not know
    what is descritor, rule, or region in the context of NCL language, please
    see the [NCL Handbook](http://handbook.ncl.org.br).
  * [sNCL (Simple NCL)](http://github.com/telemidia-ma/sncl) is a simpler,
     alternative, syntax to write NCL documents.

### Conversion tools

  * [Diet NCL](https://github.com/gflima/dietncl) is a tool to remove the
    syntactic sugar from NCL documents.
  * [ppt2ncl](https://github.com/robertogerson/ppt2ncl) is a simple tool to
    convert PPT files into NCL documents.
  * [ncl2html](https://github.com/flavioribeiro/ncl2html): NCL Raw Profile
    application on your browser.
  * [ncls3d](https://github.com/robertogerson/ncls3d) is a lua script to convert
    an NCL application to its stereoscopic counterpart.  The final application
    is ready to run on stereoscopic 3D displays.  It allows both off-line
    conversion, and on-line (client-side) conversion---through an NCLua media
    object.
  * [Lua2NCL](https://github.com/danielsm/Lua2NCL) is a Lua-based API to create
    NCL documents.


## Books and tutorials

### NCL only
  * [NCL Handbook](http://handbook.ncl.org.br) details each NCL element and
    their attributes.
  * [Programando em NCL 3.0](http://www.ncl.org.br/programandoncl) (portuguese)
    is the official user-oriented documentation of NCL.  It has a detailed
    description of the language and a lot of examples.
  * [Building Interactive Audiovisual Programs Using NCL 3.0 (2nd edition)](http://www.telemidia.puc-rio.br/sites/telemidia.puc-rio.br/files/TutorialNCL3.0-2ed-3rev.pdf)
    (portuguese).
  * [NCL Tooltips](http://www.telemidia.puc-rio.br/~roberto/ncl-tooltips)
    provides a summary description and authoring hints for each NCL element and
    attribute.  They provide context-sensitive support for authors and tools.
  * [NCL Composer User Manual](http://ncl-composer-manual.readthedocs.io)
    (portuguese).

### NCLua integration:

  * [NCLua Tutorial](http://www.telemidia.puc-rio.br/~francisco/nclua/tutorial/)
    (portuguese)
  * [NCLua shortcourse](http://www.telemidia.puc-rio.br/files/biblio/2009_10_santanna.pdf)
    (portuguese)

### Slides and courses material
  * [Programming in NCL and NCLua](http://www.telemidia.puc-rio.br/~lfgs/doku.php?id=extensao:programandoncl)
    (portuguese) by Prof. Luiz Fernando Gomes Soares.


## Application Examples

### Repositories

  * [NCL Club](http://club.ncl.org.br) is a repository of complete NCL applications.
  * [Digital TV Applications by Brazilian Communication Ministry](http://gingabr.comunicacoes.gov.br)
    is a repository of t-government interactive applications.
  * [Ginga.ar Application Examples](http://tvd.lifia.info.unlp.edu.ar/ginga.ar/index.php/apps-menu)
  * [GingaAPPS](https://github.com/rmcs87/GingaAPPS)

### Test suites

  * [ITU-T - Ginga-NCL Test Suite](http://testsuite.gingancl.org.br)
  * [Ginga.ar Test Suite](http://tvd.lifia.info.unlp.edu.ar/ginga.ar/index.php/testsuite-menu)

### Showcases

  * [Remote Lab - UFSC](https://www.youtube.com/embed/UkDDCmK5q9c)
  * [Conheça o Brasil 4D](http://www.youtube.com/embed/T5hE0l_NkfY)
  * [Aplicativo Interativo Aprendiz (Rede Record)](https://www.youtube.com/watch?v=NpzFlAHdXR8)
  * [Aplicativo Interativo Ídolos (Rede Record)](https://www.youtube.com/watch?v=VOjQMAl0fec)
  * [Projeto Trapézio (USP)](https://www.youtube.com/watch?v=cbmh-rv0qi8)
  * [Vídeo: interatividade (Ginga) na Copa do Mundo](https://www.youtube.com/watch?v=uryEkVX3LK4)
  * [Plataforma de TV Digital CERTI](https://www.youtube.com/watch?v=QnIJMGFEKhI)
  * [Aplicativo Interativo Ginga: Caixa Econômica](https://www.youtube.com/watch?v=km2Ugol3zsI)
  * [Ciência Sem Limites - TV Digital Interativa](https://www.youtube.com/watch?v=ykvy-5IjWMQ)
    (12/05/2014)
  * [Programa ao Cubo](https://vimeo.com/85625655)

### Other applications

  * [TocantinsFight](https://github.com/luizcarvalho/TocantinsFight) is a
    Ginga-NCL Appication for Tocantins Mixed Martial Art in Local TV.
  * [GingaChatTV](https://github.com/luismeloni/GingaChatTV)
  * [EnqueteTVD](https://github.com/manoelcampos/EnqueteTVD) is a quiz
    application digital TV supporting the return channel.
  * [TVDQuiz](https://github.com/manoelcampos/TVDQuiz) Aplicação de Quiz para o
    Sistema Brasileiro de TV Digital (SBTVD/ISDB-TB).
  * [Teclado Virtual (Virtual Keyboard)](http://code.google.com/p/tecladovirtualgingancl)
  * [Ginga-Pizza](http://code.google.com/p/ginga-pizza)
  * [Ginga Hero](https://github.com/rmcs87/GingaHero)
  * [TodosContraDengue](https://github.com/carvalhorafael/TodosContraDengue)
  * [JogoDaVelha](https://github.com/carvalhorafael/JogoDaVelha)
  * [GingaBemTeVi](http://sourceforge.net/projects/gingabemtevi)
  * [Ginga Unisinos](http://sourceforge.net/projects/ginga-unisinos)
  * [Flappy Ginga](https://www.youtube.com/watch?v=KzZ6Rd6c6mg&list=UUyVuQq2Iyr5e8ecocaGq-OQ)


## Ginga Communities
NCL is part of the specification of Ginga middleware, the standard for
terrestrial digital TV in most part of Latin America.

Here, you can find the link for some of the communities in different countries
working with Ginga and NCL:

  * [Ginga Brasil](http://www.softwarepublico.gov.br/ver-comunidade?community_id=1101545)
  * [Ginga Argentina](http://comunidad.ginga.org.ar)
  * [Ginga Peru](http://www.gingaperu.org/comunidad)
  * [Ginga Equador](http://www.ginga.org.ec/gingaec/index.php)
  * [Ginga Bolivia](http://ginga.softwarelibre.org.bo)
  * [Ginga Chile](http://www.comunidadginga.cl)

## News

A non-extensive list of news about Ginga and NCL.

  * [Para Intel, TV Digital é uma porta brasileira para a IoT](https://www.youtube.com/watch?v=orCPmSNRQqA) (23/07/2016)
  * [Intel: Brasil precisa articular o uso do Ginga como padrão global de interatividade](https://www.youtube.com/watch?v=wmJyjcRabDo) (14/07/2016)
  * [Projeto dá acesso a serviços do governo pela televisão e ganha prêmio](http://www.opovo.com.br/app/maisnoticias/brasil/2014/08/28/noticiasbrasil,3305265/projeto-da-acesso-a-servicos-do-governo-pela-televisao-e-ganha-premio.shtml) (28/08/2014)
  * [Emissoras de TV com sinal digital estudam implantar serviços do Detran](http://www.portaliguacu.com.br/web-e-tecnologia/emissoras-de-tv-com-sinal-digital-estudam-implantar-servicos-do-detran-1788) (05/07/2014)
  * [Totvs e Panasonic anunciam solução para TV interativa em empresas](http://computerworld.com.br/tecnologia/2014/06/30/totvs-e-panasonic-anunciam-solucao-para-tv-interativa-em-empresas) (30/06/2014)
  * [Totvs e Panasonic: canais de TV internos](http://www.baguete.com.br/noticias/30/06/2014/totvs-e-panasonic-canais-de-tv-internos) (30/06/2014)
  * [Ginga será obrigatório nos conversores de TV Digital para Bolsa Família](http://convergenciadigital.uol.com.br/cgi/cgilua.exe/sys/start.htm?infoid=37181&sid=7#.U7_yjHKqfqQ) (10/07/2014)
  * [O que é o Ginga?](http://tecnologia.ig.com.br/especial/o-que-e-o-ginga/n1597734545853.html) (09/04/2012)
  * [No feriado, população pode acessar serviços do Detran pela TV](http://www.aen.pr.gov.br/modules/noticias/article.php?storyid=79995&tit=No-feriado-populacao-pode-acessar-servicos-do-Detran-pela-TV&ordem=1000)
  * [Infográfico: Como funciona o Ginga](http://tecnologia.ig.com.br/especial/infografico-como-funciona-o-ginga/n1597734566733.html)
  * [TV Digital e desenvolvimento: padrões, tecnologias e oportunidades](http://www.infoq.com/br/articles/tvdigital-entrevista) (26/11/2012)
  * [Ginga: A TV Digital com interatividade](http://tvfoco.pop.com.br/tv-foco/ginga-a-tv-digital-com-interatividade) (09/06/2012)

## Other related links

  * [Ginga DF](http://www.gingadf.com/blogGinga)
  * [Manoel Campos' Home Page](http://manoelcampos.com)
  * [TVDI](http://www.tvdi.inf.br/site)
  * [Grupo Ginga Goias](http://grupogingagoias.com.br)
  * [Ginga TV Digital](http://gingatvdigital.com)

