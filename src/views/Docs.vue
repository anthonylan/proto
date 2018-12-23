<template>
  <div class="docs">
    <div class="container-gap">
      <hr>
      <h1 class="custom">Buttons</h1>
     <div class="row">
      <div class="col-9">
         <!-- BUTTONS -->
            <a href="#" class="button">Anchor Button</a>
          <button>Button Element</button>
          <input type="button" value="Button Input">
          <input type="submit" value="Submit Input">

          <a href="#" class="button colored">Anchor Button</a>
          <button class="colored">Button Element</button>
          <input class="colored" type="button" value="Button Input">
          <input class="colored" type="submit" value="Submit Input">
      </div>
      <div class="col-3"></div>
     </div>
      <div class="row">
        <div class="col-12">
      <prism>
      &lt;a href="#" class="button"&gt;Anchor Button&lt;/a&gt;
      &lt;button&gt;Button Element&lt;/button&gt;
      &lt;input type="button" value="Button Input"&gt;
      &lt;input type="submit" value="Submit Input"&gt;

      &lt;a href="#" class="button colored"&gt;Anchor Button&lt;/a&gt;
      &lt;button class="colored"&gt;Button Element&lt;/button&gt;
      &lt;input class="colored" type="button" value="Button Input"&gt;
      &lt;input class="colored" type="submit" value="Submit Input"&gt;
      </prism>
        </div>
      </div>
      <hr>
      <h1 class="custom">grids</h1>
      <div class="grids">
         <div class="row">
          <div class="col-1">one</div>
          <div class="col-11">eleven</div>
        </div>
        <div class="row">
          <div class="col-2">two</div>
          <div class="col-10">ten</div>
        </div>
        <div class="row">
          <div class="col-3">three</div>
          <div class="col-9">nine</div>
        </div>
        <div class="row">
          <div class="col-4">four</div>
          <div class="col-8">eight</div>
        </div>
        <div class="row">
          <div class="col-5">five</div>
          <div class="col-7">seven</div>
        </div>
        <div class="row">
          <div class="col-6">six</div>
          <div class="col-6">six</div>
        </div>
        <div class="row">
          <div class="col-12">twelve</div>
        </div>
      </div>
      <prism>
     &lt;--- Container comes in two variety---&gt;
      &lt;div class="container"&gt; 80% &lt;/div&gt;
      &lt;div class="container-gap"&gt; 70% &lt;/div&gt;

      &lt;div class="row"&gt;
        &lt;div class="col-1"&gt; One &lt;/div&gt;
        &lt;div class="col-11"&gt; Eleven &lt;/div&gt;
      &lt;/div&gt;
      &lt;div class="row"&gt;
        &lt;div class="col-2"&gt; Two &lt;/div&gt;
        &lt;div class="col-10"&gt; Ten &lt;/div&gt;
      &lt;/div&gt;
      &lt;div class="row"&gt;
        &lt;div class="col-3"&gt; Three &lt;/div&gt;
        &lt;div class="col-9"&gt; Nine &lt;/div&gt;
      &lt;/div&gt;
      &lt;div class="row"&gt;
        &lt;div class="col-4"&gt; Four &lt;/div&gt;
        &lt;div class="col-8"&gt; Eight &lt;/div&gt;
      &lt;/div&gt;
      &lt;div class="row"&gt;
        &lt;div class="col-5"&gt; Five &lt;/div&gt;
        &lt;div class="col-7"&gt; Seven &lt;/div&gt;
      &lt;/div&gt;
      &lt;div class="row"&gt;
        &lt;div class="col-6"&gt; Six &lt;/div&gt;
        &lt;div class="col-6"&gt; Six &lt;/div&gt;
      &lt;/div&gt;
      &lt;div class="row"&gt;
        &lt;div class="col-12"&gt; Twelve &lt;/div&gt;
      &lt;/div&gt;
      </prism>
      <hr>
       <h1 class="custom">typography</h1>
      <div class="row">
        <div class="col-4">
          <h1>Heading</h1>
          <h2>Heading</h2>
          <h3>Heading</h3>
          <h4>Heading</h4>
          <h5>Heading</h5>
          <h6>Heading</h6>
        </div>
        <div class="col-8">
          <prism>
            &lt;h1&gt;Heading&lt;/h1&gt;
            &lt;h2&gt;Heading&lt;/h2&gt;
            &lt;h3&gt;Heading&lt;/h3&gt;
            &lt;h4&gt;Heading&lt;/h4&gt;
            &lt;h5&gt;Heading&lt;/h5&gt;
            &lt;h6&gt;Heading&lt;/h6&gt;
          </prism>
        </div>
      </div>
     
        
      <hr>
    <h1 class="custom">Form inputs</h1>
      <form>
        <div class="row">
            <div class="col-6">
                <label>Name</label>
                <input type="text" placeholder="Enter Name...">
            </div>
            <div class="col-6">
                <label>Subject</label>
                    <select>
                        <option value="sale">Proposal</option>
                        <option value="sale">Enquiring</option>
                        <option value="sale">Report</option>
                    </select>
            </div>
        </div>
        <div class="row">
                <div class="col-12">
                    <label>Message</label>
                  <textarea rows="6" placeholder="Message"></textarea>
              </div>
          </div>
       <button type="submit" class="colored">Send message</button>
    </form>
    <prism>
      &lt;form&gt;
        &lt;div class="row"&gt;
            &lt;div class="col-6"&gt;
                &lt;label&gt;Name&lt;/label&gt;
                &lt;input type="text" placeholder="Enter Name..."&gt;
            &lt;/div&gt;
            &lt;div class="col-6"&gt;
                &lt;label&gt;Subject&lt;/label&gt;
                    &lt;select&gt;
                        &lt;option value="sale"&gt;Proposal&lt;/option&gt;
                        &lt;option value="sale"&gt;Enquiring&lt;/option&gt;
                        &lt;option value="sale"&gt;Report&lt;/option&gt;
                    &lt;/select&gt;
            &lt;/div&gt;
        &lt;/div&gt;
        &lt;div class="row"&gt;
                &lt;div class="col-12"&gt;
                    &lt;label&gt;Message&lt;/label&gt;
                  &lt;textarea rows="6" placeholder="Message"&gt;&lt;/textarea&gt;
              &lt;/div&gt;
          &lt;/div&gt;
       &lt;button type="submit" class="colored"&gt;Send message&lt;/button&gt;
    &lt;/form&gt;
    </prism>
    <hr>
    <h1 class="custom">Lists</h1>
    <div class="row">
      <div class="col-6">
        <ul>
            <li>Unordered List</li>
            <li>They have basic styles</li>
            <li>
                <ul>
                        <li>Nested Unordered List</li>
                </ul>
            </li>
            <li>Another List</li>
        </ul>
      </div>
      <div class="col-6">
      <ol>            
            <li>Ordered List</li>
            <li>They have basic styles</li>
            <li>
                <ol>
                        <li>Nested Ordered List</li>
                </ol>
            </li>
            <li>Another List</li>
        </ol>
      </div>
    </div>
    <prism>
      &lt;ul&gt;
        &lt;li&gt;Unordered List&lt;/li&gt;
        &lt;li&gt;They have basic styles&lt;/li&gt;
        &lt;li&gt;
            &lt;ul&gt;
                  &lt;li&gt;Nested Unordered List&lt;/li&gt;
            &lt;/ul&gt;
        &lt;/li&gt;
        &lt;li&gt;Another List&lt;/li&gt;
    &lt;/ul&gt;
  
      &lt;ol&gt;            
          &lt;li&gt;Ordered List&lt;/li&gt;
          &lt;li&gt;They have basic styles&lt;/li&gt;
          &lt;li&gt;
              &lt;ol&gt;
                    &lt;li&gt;Nested Ordered List&lt;/li&gt;
              &lt;/ol&gt;
          &lt;/li&gt;
          &lt;li&gt;Another List&lt;/li&gt;
      &lt;/ol&gt;
    </prism>
    <hr>
    <h1 class="custom">table</h1>
       <table>
        <thead>
          <tr>
            <th>Name</th>
            <th>Age</th>
            <th>Sex</th>
            <th>Location</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Sara Conel</td>
            <td>23</td>
            <td>Female</td>
            <td>Miami</td>
          </tr>
          <tr>
            <td>Stone White</td>
            <td>22</td>
            <td>Male</td>
            <td>Chicago</td>
          </tr>
        </tbody>
      </table>
      <prism>
        &lt;table&gt;
        &lt;thead&gt;
          &lt;tr&gt;
            &lt;th&gt;Name&lt;/th&gt;
            &lt;th&gt;Age&lt;/th&gt;
            &lt;th&gt;Sex&lt;/th&gt;
            &lt;th&gt;Location&lt;/th&gt;
          &lt;/tr&gt;
        &lt;/thead&gt;
        &lt;tbody&gt;
          &lt;tr&gt;
            &lt;td&gt;Sara Conel&lt;/td&gt;
            &lt;td&gt;23&lt;/td&gt;
            &lt;td&gt;Female&lt;/td&gt;
            &lt;td&gt;Miami&lt;/td&gt;
          &lt;/tr&gt;
          &lt;tr&gt;
            &lt;td&gt;Stone White&lt;/td&gt;
            &lt;td&gt;22&lt;/td&gt;
            &lt;td&gt;Male&lt;/td&gt;
            &lt;td&gt;Chicago&lt;/td&gt;
          &lt;/tr&gt;
        &lt;/tbody&gt;
      &lt;/table&gt;
      </prism>
    </div>
    <footer>
        <p>&copy; {{now}} | Made with love by <a href="https://github.com/anthonylan/">Anthony Charles</a> </p>
    </footer>
  </div>
</template>


<script>

import "prismjs/prism";
import "prismjs/themes/prism.css";
import Prism from 'vue-prism-component'


export default {
  name: 'docs',
  components:{
      Prism
  },
  data (){
    return{
        now: new Date().getFullYear(),
    }
  }
 
}
</script>



<style lang="scss" scoped>
$primary: #2185d0;

.docs{
  padding-top: 50px;
  color: #333;
  line-height: 1.7;
  .main{
    padding-top: 50px;
  }
  hr{
    background: #ddd;
    height: 1px;
    border: none;
  }
  p{
    font-size: 1.1rem;
  }
  h1.custom{
    font-size: 1rem;
    text-transform: uppercase;
    font-weight: bold;
    margin-top: 1.4rem;
    margin-bottom: 1.5rem;
    text-decoration: underline;
    color: #555;
  }

  .grids{
        .row{
      div{
          background: #fff;
          padding: .6rem 1rem;
          border: 1px solid #ddd;
          border-radius: 4px;
          margin-top: .5rem;
          box-sizing: border-box;
          text-transform: uppercase;
          text-align: center;
      }
  }
  }
  input[type='button'],button, .button{
    margin-top: 10px;
    margin-right: 10px;
  }
  pre{
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 5px;
  }
  footer{
      text-align: center;
      height: 100px;
      background: #f8f9f9;
      color: #555;
      padding-top: 30px;
      margin-top: 40px;
      box-sizing: border-box;
  }
}


//PROTO STYLES
/*CONTAINER*/

.container{
    width: 80%;
    margin: 0 auto;
}
.container-gap{
    width: 70%;
    margin: 0 auto;
}

/*GRID*/
.row{
    display: flex;
    justify-content: space-between;
    .col-1{
        flex-basis: 7.66666666667%; 
    }
    .col-2{
        flex-basis: 15.3333333333%; 
    }
    .col-3{
        flex-basis: 24%; 
    }
    .col-4{
        flex-basis: 32.6666666667%; 
    }
    .col-5{
        flex-basis: 40.3333333333%; 
    }
    .col-6{
        flex-basis: 49%;
    }
    .col-7{
        flex-basis: 56.6666666667%; 
    }
    .col-8{
        flex-basis: 65.3333333333%; 
    }
    .col-9{
        flex-basis: 74.0%;
    }
    .col-10{
        flex-basis: 91.3333333333%; 
    }
    .col-10{
        flex-basis: 82.6666666667%; 
    }
    .col-11{
        flex-basis: 91.3333333333%;
    }
    .col-12{
        flex-basis: 100%;
    }
    @media (max-width:550px) {
        flex-direction: column;
    }
}
/*TYPOGRAPHY*/
h1, h2, h3, h4, h5, h6{
    font-weight: 400;
    margin: 0;
}
h1{
    font-size: 2.8rem;
}
h2{
    font-size: 2.2rem;
}
h3{
    font-size: 1.9rem;
}

h4{
    font-size: 1.5rem;
}
h5{
    font-size: 1.3rem;
}
h6{
    font-size: 1.1rem;
}

//LIST
ul{
    li{
        list-style: circle;
    }
}
/*BUTTONS*/
button, input[type='submit'],input[type='button'], .button{
    padding: 10px 18px;
    display: inline-block;
    margin: 5px 0;
    background-color: white;
    color: rgba(0, 0, 0, .6);
    font-size: .9rem;
    font-weight: 400;
    text-shadow: none;
    text-decoration: none;
    text-transform: uppercase;
    cursor: pointer;
    border: 1px solid #ddd;
    border-radius: 4px;
    outline: none;
    transition: all .2s ease-in-out;
    &:hover{
        border: 1px solid #999;
        color: rgba(0, 0, 0, .7);
    }
}
//Reset button styles
.button{
    padding: 9px 15px;
}
//Colored Button
input.colored, .colored{
    background: $primary;
    color: white;
    border-color: $primary;
    &:hover{
        border-color: darken($primary, 5);
        background: darken($primary, 5);
        color: white;
    }
}
/*FORM INPUTS*/
input[type='text'], input[type='email'],
 input[type='search'], select, textarea{
     width: 100%;
     padding: 10px;
     margin: 10px auto;
     box-sizing: border-box;
     border: 1px solid #ddd;
     border-radius: 4px;
     color: #555;
     &:focus{
         outline: none;
         border: 1px solid $primary;
     }
 }
 label{
     font-weight: bold;
 }
 table{
    width: 100%;
    border-radius: 5px;
    border-spacing: 0;
    border-collapse: collapse;
    font-size: .9rem;
    thead{
       tr{
           border-bottom: 1px solid #ddd;
       }
        th{
            text-align: left;
            padding: 10px;
            margin: 0;
        }
        th:first-child{
            border-radius: 5px 0 0 0;
        }
        th:last-child{
            border-radius: 0 5px 0 0;
        }
    }
    tbody{
        td{
            padding: 10px;
            text-align: left;
            background: white;
            border-bottom: 1px solid #ddd;
           
        }
    }
   
}

</style>
