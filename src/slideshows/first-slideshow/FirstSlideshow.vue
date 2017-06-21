<template lang='pug'>
#MyFirstSlideshow
  .eg-slideshow
    slide 
      h2.title Shay Doherty

      img.stiona(src='./stiona_400x400.jpg')
      p
      
      div.center.green @shaydmusic
      div.center Technical Specialist Person
       
      
    slide(enter='bounceInRight' leave='fadeOut')
      h1.title Vue.js @ Stiona
      img.logo(src='./vue-logo.png')

      blockquote
        p <i>I really care about the approachability part of Vue, which is rooted in the belief that technology should be enabling more people to build things</i>
        p <strong>Evan You</strong>, creator of Vue.js — <strong>Between The Wires</strong>
     
    slide(enter='bounceInRight' leave='fadeOut') 
      h3.title Stiona's Clients (2004-)

      ol.reasons
        li.reason-item Bank of Scotland/HBOS (Consultancy)
        li.reason-item Axa (Consultancy, product development)
        li.reason-item Department of Agriculture  (Single Farm Payment)
        li.reason-item NIDirect (Working on Digital Toolkit and Transformation)
        li.reason-item Bank of Ireland (Swift IBAN Conversion API)
        li.reason-item Ourselves (Klubfunder.com, Achta.com)
      

    
    slide(enter='bounceInRight' leave='fadeOut') 
      h3.title Projects @ Stiona 
      
      h4.center 2013 Multi-Tenant Platform
      blockquote
        p  
           ss - ASP.NET MVC/Webapi REST Layer,<br> 
           ui - UI code: RequireJS, Knockout.js and Sammy.js (Routing)<br>
           bl - Javascript minification using a combination of node and r.js<br>
           pf - Microsoft Azure

      h4.center Team Size 2 Full stack devs
      
    slide(enter='bounceInRight' leave='fadeOut' :steps="4") 
      h3.title Projects @ Stiona (2)

      ol.reasons
        li.reason-item(v-if='step >= 2') Klubfunder.com (Free fundraising platform for amateur sports clubs)
        li.reason-item(v-if='step >= 3') Achta.com (SEPA Direct Debit and Swift Account conversion platform)
        li.reason-item(v-if='step >= 4') NIDirect Digital Toolkit (Government Software as a Service platform)

    slide(enter='bounceInRight' leave='fadeOut') 
      h3.title Fast forward 2016...

      h1.center Team Size 10

      ol.reason
        li.reason-item 5 Full stack devs
        li.reason-item 1 part time  web designer
        li.reason-item 2 Selenium Testing devs (1 uni student)
        li.reason-item 1 Manager
        li.reason-item 1 Kanban board 
        li.reason-item And seemingly infinte backlog....
  
    slide(enter='bounceInRight' leave='fadeOut') 
      h3.title Setting the scene...

      img.giphy(src="https://media.giphy.com/media/TzBLLOlPa4LZu/giphy.gif")

      h4.title.center ....2016 & we are reflecting on our existing assets
 
    slide(enter='bounceInRight' leave='fadeOut' :steps="6") 
      h3.title Our front end dev build becoming painful

      ol.reasons
        li.reason-item(v-if='step >= 2') Ever growing codebase
        li.reason-item(v-if='step >= 3') Existing framework with knockout/RequireJS is showing its age
        li.reason-item(v-if='step >= 3') Component architecture in knockout 3.4 is clunky
        li.reason-item(v-if='step >= 3') Its free and easy, devs have more decisions to make (lacking consistency) 
        li.reason-item(v-if='step >= 5') Clients want Mobile apps also...
        li.reason-item(v-if='step >= 6') Looking with jealous eyes at ES6 Module Syntax!
    


    slide(enter='bounceInRight' leave='fadeOut') 
      h3.title 3 years down the line, with a shit tonne of projects....
      img.giphy(src="https://media.giphy.com/media/l0HlCqV35hdEg2GUo/giphy.gif")

    slide(enter='bounceInRight' leave='fadeOut') 
      h3.title What are we looking for?

      ol.reason
        li.reason-item Leaner, faster code
        li.reason-item Better modularized coding environment
        li.reason-item Easier testability
        li.reason-item Good and active dev community
        li.reason-item Rich ecosystem of plugins
        li.reason-item Build web and mobile apps with one codebase

    slide(enter='bounceInRight'  leave='fadeOut' :steps="5") 
      h3.title Evaluating whats out there...

      ol.reason
        li.reason-item(v-if='step >= 2')  Angular.js 1
        li.reason-item(v-if='step >= 3')  Angular.js 2/4 
        li.reason-item(v-if='step >= 4')  React
        li.reason-item.green(v-if='step >= 5')  Vue

      blockquote(v-if='step >= 5')
        p Hacker news Vue.js receiving alot of love...

    slide(enter='bounceInRight' leave='fadeOut' :steps="4") 
      h3.title Introducing Vue.js
     
      ol.reason
        li.reason-item.green(v-if='step >= 2') Approachable
          ul.reason
            li.reason-item lightweight, just drop in a script reference to begin...
        li.reason-item.green(v-if='step >= 3') Versatile
          ul.reason
              li.reason-item Simple, minimal core, incrementally adopt supporting libraries
        li.reason-item.green(v-if='step >= 4') Performant
          ul.reason
            li.reason-item 19kb min + gzip, blazing fast virtual dom!
  
    slide(enter='bounceInRight' leave='fadeOut') 
      h3.title Starting Vue.js
     
      iframe(width="100%" height="300" src="//jsfiddle.net/chrisvfritz/50wL7mdz/embedded/js,html,css,result/dark/" allowfullscreen="allowfullscreen" frameborder="0")
     
    slide(enter='bounceInRight' leave='fadeOut') 
      h3.title Vue.js basics

      ol.reason
        li.reason-item Directives - v-for, v-on, v-if, v-bind:href="url"
        li.reason-item Filters -  message | capitalize
        
      <iframe width="100%" height="300" src="//jsfiddle.net/shaydoc/3Lt0jgm4/16/embedded/js,html,css,result/dark/" allowfullscreen="allowfullscreen" frameborder="0"></iframe>
     
    slide(enter='bounceInRight' leave='fadeOut')
      h3.title Vue.js Lifecyle
      
      <iframe width="100%" height="300" src="//jsfiddle.net/shaydoc/Ljh205vf/5/embedded/js,html,css,result/dark/" allowfullscreen="allowfullscreen" frameborder="0"></iframe>

    slide(enter='bounceInRight' leave='fadeOut')
      h3.title Vue.js Components

    slide(enter='bounceInRight' leave='fadeOut')
      h3.title Vue.js Slots

    slide(enter='bounceInRight' leave='fadeOut')
      h3.title Vue.js Transitions & Keep Alive

    slide(enter='bounceInRight' leave='fadeOut')
      h3.title Vue.js Single Page Components
    
    slide(enter='bounceInRight' leave='fadeOut')
      h3.title Developers be like... 
      
      img.giphy(src="https://media.giphy.com/media/3NtY188QaxDdC/giphy.gif")  

    slide(enter='fadeIn')
      h3.title Want cool effects?
      p.
        Code your own, or try stealing for the other slideshows !
</template>

<script>
import eagle from 'eagle.js'
export default {
  mixins: [ eagle.slideshow ],
  infos: {
    // These infos appear on the home page, below the slideshow's thumbnail
    title: 'Vue Js and Webpack @ Stiona',
    description: 'Belfast JS Presentation',
    path: 'vuejs-at-stiona'
  }
}
</script>

<style lang='scss'>
@import url('https://fonts.googleapis.com/css?family=Dosis:500');
@import url('https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,600|Roboto Mono');
 
#MyFirstSlideshow{
  .eg-slideshow{
    font-family: 'Source Sans Pro';
    background-color: #f7f7f7;
    
    .title{
      font-family: 'Dosis';
    }
  
  

    p.center{
      text-align: center;
    }

    .eg-slide{
      .eg-slide-content{
        width: 25em;
        max-width: 80%;
        margin: 0 auto;
          h1.title {
          font-size: 3em;
          font-family: 'Dosis';
          font-weight: 300;
          margin-bottom: 60px;
          
        }
        blockquote{
          margin-left:90px;
          border-left: 2px solid #000;
          padding-left: 15px;
          font-size: 0.8em;
        }
        .reasons{
          margin-top: 40px;
          .reason-item{
            padding: 10px 10px 10px 10px;
          }
        }

      
      }
    }
  }
  .eg-slide-content{
    width: 25em;
    max-width: 80%;
    margin: 0 auto;
  }

  .logo {
    display: block;
    margin: 0 auto;
    max-height: 8em;
  }

  .giphy{
     display: block;
    margin: 0 auto; 
  }

  .stiona{
    max-height: 8em;
     display: block;
    margin: 0 auto; 
  }

  .green {
    color : rgb(79, 192, 141);
    font-family: 'Dosis';
    font-weight: bold;
  }
}
</style>
