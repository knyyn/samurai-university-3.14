
* {
  box-sizing: border-box;
}

body {
  font-family: "Noto Selif JP", serif;
  background-color: #fff;
  margin: 0 0 0 0;
}

header {
  background-color: black;
}



a, a:hover, a:visited, a:active, a:link {
  text-decoration: none;
}

/* ===============
    PC用スタイル
=============== */ 

@media screen and (min-width: 992px) {


  /* 横幅設定 */
  main {
    max-width: 100%;
    min-width: 100%;
    margin-top: 80px;
  }

  /* ヘッダー */
  header {
    margin: 0 0 0 0;
    position: fixed;
    z-index: 100;
    top: 0;
    width: 100%;
    padding: 0 20px 0 20px;
    align-items: center;
  }

  .area_logo_header_1 {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .area_logo_header_1 span {
    font-weight: bold;
    color: #fff;
    font-size: 18px;
    position: relative;
    bottom: 18px;
    left: 5px;
  }

  .imag {
    top: 12px;
    left: 4px;
  }

  .nav_pc {
    color: #fff;
    display: inline-block;
  }


  .list_nav_header_1 {
    display: flex;
    text-align: left;
    list-style: none;
    color: #fff;
  }

  .nav_link {
    color: #384158;
    font-size: 18px;
  }

  .nav_link p {
    color: #fff;
    margin: 0 0 0 0;
    font-size: 14px;
  }

  ul > li + li {
    margin-left: 40px;
  }

  .menu_sp {
    display: none;
  }

  .nav_sp {
    display: none;
  }

  .list_nav_header_2 {
    display: none;
  }
  
  /* メインビジュアル */

  .main_visual_pic1 {
    position: relative;
    bottom: 50px;
    text-align: center;
  }

  .main_visual_pic2 {
    position: absolute;
    left: 20%;
    right: 20%;
    top: 10%;
  }

  .main_pic {
    width: 100%;
  }

  .main_title {
    margin: auto;
    color: #92def1;
    font-size: 50px;
    letter-spacing: 3.5px;
  }

  .main_contents {
    font-family: "Roboto", sans-serif;
    color: #fff;
    font-size: 16px;
    letter-spacing: 2.5px;
    position: absolute;
    left: 10%;
    right: 10%;
    
  }

  /* 　NEWSとEVENT */

  #div_1 {
    width: 100%;
    margin-bottom: 30px;
    background: #fff;
  }

  .news_contents_1 {
    padding: 0px 5%;
  }

  .news_contents_2 {
    display: flex;
    margin-top: 35px;
  }

  .top_title {
    color: black;
    font-size: 30px;
    letter-spacing: 3px;
    margin: 0 0 0 0;
  }

  .top_title_sub {
    font-family: "Roboto", sans-serif;
    letter-spacing: 0.7px;
    color: grey;
    font-size: 14px;
    border-bottom: 2px solid #4aa0b5;
    margin-bottom: 20px;
    width: fit-content;
  }

  .date {
    color: #808080;
  }

  .news_topic:not(:last-child) {
    /* padding-bottom: 5px; */
    border-bottom: solid 2px lightgray;
  }

  .news_report {
    font-weight: bold;
    font-size: 17px;
    color: black;
    margin-bottom: 5px;
  }

  .all-contents {
    padding: 15px;
    flex: 1;
  }

  .courses_contents {
    display: inline-block;
  }

  .event:not(:last-child) {
    padding-bottom: 10px;
    border-bottom: solid 2px lightgray;
  }

  .event {
    display: flex;
    padding: 10px 0;
  }

  .event_title {
    font-size: 17px;
    font-family: "Noto Selif JP", serif;
    font-weight: bold;
    color: black;
    margin: 0;
  }

  .event_post_contents {
    position: relative;
    color: #808080;
  }

  .event_contents {
    padding-left: 50px;
    flex: 6;
  }

  .calendar_box {
    display: inline-block;
    align-items: center;
    width: 100px;
    height: 100px;
    padding: 10px;
    background-color: #555555;
    color: #fff;
  }

  .calendar_box > .calendar_contents {
    border: 1px solid #fff;
  }

  .calendar_month {
    font-size: 12px;
    font-family: "Noto Selif JP", serif;
    text-align: center;
    padding-top: 4px;
  }

  .calendar_day {
    font-size: 40px;
    font-family: "Noto Selif JP", serif;
    text-align: center;
  }

  /* COURSE */

  #courses { 
    width: 100%;
    padding-top: 30px;
    padding-bottom: 60px;
  }

  .coures_image {
    max-width: 100%;
    border-radius: 10px 10px 0 0;
  }

  #all-contents2 {
    padding: 0px 5%;
  }

  .courses_1 {
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
  }

  .courses_2 {
    flex-basis: 0;
    flex-grow: 1;
    max-width: 100%;
  }

  .courses_title {
    max-width: 600px;
    width: fit-content;
    margin: 0 auto;
    color: black;
  }

  .top_title_sub2 {
    border-bottom: 2px solid #4aa0b5;
    line-height: 1.85;
    margin: 0 auto;
    width: fit-content;
  }

  .courses_contents {
    margin-top: 25px;
    display: flex;
    /* margin-right: -15px; */
    /* margin-left: -15px; */
  }

  .course {
    /* flex: 3; */
    position: relative;
    margin-right: 15px;
    margin-left: 15px;
    width: 100%;
    background: #fff;
    box-sizing: 0px 1px 10px rgba(29, 34, 47, 0.1);
    box-shadow: 1px 2px 2px 1px lightgray;
    border-radius: 10px;
  }

  .course_title {
    height: 2.3em;
    padding: 0 20px;
    font-size: 22px;
  }

  .course_text {
    color: #808080;
    margin-top: 13px;
    height: 2.3em;
    font-size: 14px;
    padding: 0 20px;
  }

  .course_footer_content {
    width: 100%;
    padding: 20px 20px;
    text-align: end;
  }

  .course_footer_content_2 {
    color: #4aa0b5;
    font-size: 16px;
    font-weight: 700;
    margin-left: auto;
  }

  /* 数字 */

  .counter {
    width: 100%;
  }

  .counter_background {
    position: absolute;
    width: 100%;
  }

  .counter_1 {
    width: 100%;
    padding: 0px 5%;
  }

  .counter_2 {
    position: relative;
    box-sizing: border-box;
  }

  .counter_4 {
    padding-top: 20px;
    padding-bottom: 50px;
  }

  .counter_5 {
    margin-top: 40px;

  }

  .counter_7 {
    display: flex;
    justify-content: space-around;
    align-items: center;
    text-align: center;
    color: #fff;
  }

  .counter_contents {
    padding: 0 40px;
  }

  .counter_8 {
    display: flex;
  }

  .counter_8 .imag2 {
    width: 30%;
    height: 30%;
    object-fit: cover;
    position: relative;
    top: 5px;
    right: 5px;
  }

  .counter_8 .imag4 {
    width: 25%;
    height: 25%;
    object-fit: cover;
    position: relative;
    top: 5px;
    right: 5px;
  }

  .counter_8 .imag3 {
    width: 35%;
    height: 35%;
    object-fit: cover;
    position: relative;
    top: 5px;
    right: 5px;
  }

  .professor_counter {
    margin: 0; 
    font-size: 14px; 
    letter-spacing: 3px; 
    color: #fff;
  }

  .graduate_counter {
    margin: 0; 
    font-size: 14px; 
    letter-spacing: 3px; 
    color: #fff;
  }

  .learning_counter {
    margin: 0; 
    font-size: 14px; 
    letter-spacing: 3px; 
    color: #fff;
  }

  .award_counter {
    margin: 0; 
    font-size: 14px; 
    letter-spacing: 3px; 
    color: #fff;
  }



  .counters span {
    text-align: left;
    font-size: 40px;
    letter-spacing: 2px;
    opacity: 1;
  }

  .counters {
    margin: 0;
  }


  
  /* FOOTER */
  footer {
    display: block;
    position: relative;
    width: 100%;
    background-color: black;
    font-family: "Noto Selif JP", serif;
    padding-top: 60px;
    color: #fff;
  }

  .footer_1 {
    padding: 0 5%;
    display: flex;
  }

  .footer_right a {
    display: block;
    color: #fff;
  }

  .footer_2 {
    flex-grow: 1;
  }

  .footer_3 {
    padding-bottom: 50px;
  }

  .footer_4 {
    display: flex;
  }

  .area_logo_footer p {
    font-size: 20px;
  }

  .samurai_access {
    font-size: 15px;
    border-right: 1px solid #fff;
    padding-bottom: 5px;
    margin: 0;
  }

  .sns_footer {
    border-right: 1px solid #fff;
  }

  .sns_btns img {
    border-radius: 50%;
  } 

  .footer_center {
    margin-top: 85px;
    padding-top: 40px;
    padding-left: 60px;
    display: block;
  }

  .footer_center a {
    display: block;
    color: #b5b8be;
    font-size: 15px;
    margin-bottom: 5px;
  }

  .copy_right {
    background-color: #222222;
    padding: 5px 0;
  }

  .copy_right_text {
    color: #b5b8be;
    text-align: center;
    font-size: 12px;
  }

}

/* ===============
    スマホ用スタイル
=============== */ 

@media screen and (max-width: 600px) {

  /* 横幅設定 */
  main {
    max-width: 100%;
    min-width: 100%;
    margin-top: 80px;
  }

  /* ヘッダー */
  header {
    margin: 0 0 0 0;
    position: fixed;
    z-index: 100;
    top: 0;
    width: 100%;
    padding: 0 20px 0 20px;
    align-items: center;
  }

  .area_logo_header_1 {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .area_logo_header_1 span {
    font-weight: bold;
    color: #fff;
    font-size: 18px;
    position: relative;
    bottom: 18px;
    left: 5px;
  }

  .imag {
    top: 12px;
    left: 4px;
  }

  .nav_pc {
    display: none;
  }


  .list_nav_header_1 {
    display: none;
  }

  .list_nav_header_2 {
    display: none;
  }

  .nav_link {
    display: none;
  }

  .nav_link p {
    display: none;
  }

  ul > li + li {
    display: none;
  }

  .menu_sp {
    box-sizing: border-box;
  }

  .hamburger_open {
    margin: 30px 0 30px 0;
    width: 30%;
    color: #fff;
  }

  .ham_open {
    display: block;
    height: 2px;
    width: 80%;
    background-color: #808080;
    margin: 5px 0;
  }

  /* メインビジュアル */

  .main_visual_pic1 {
    width: 100%;
    position: relative;
    bottom: 50px;
    text-align: center;
  }

  .main_visual_pic2 {
    width: 100%;
    position: absolute;
    /* left: 20%; */
    /* right: 20%; */
    top: 12%;
  }

  .main_visual_pic2 .logo2 {
    width: 20%;
    height: 20%;
  }

  .main_pic {
    width: 100%;
    
  }

  .main_title {
    /* width: 30%;
    height: 30%; */
    margin: auto;
    color: #92def1;
    font-size: 35px;
    letter-spacing: 3.5px;
  }

  .main_contents {
    font-family: "Roboto", sans-serif;
    color: #fff;
    font-size: 12px;
    letter-spacing: 2.5px;
    position: absolute;
    left: 10%;
    right: 10%;
    
  }

  /* 　NEWSとEVENT */

  #div_1 {
    width: 100%;
    margin-bottom: 30px;
    background: #fff;
  }

  .news_contents_1 {
    padding: 0px 5%;
  }

  .news_contents_2 {
    display: flex;
    margin-top: 35px;
  }

  .top_title {
    color: black;
    font-size: 30px;
    letter-spacing: 3px;
    margin: 0 0 0 0;
  }

  .top_title_sub {
    font-family: "Roboto", sans-serif;
    letter-spacing: 0.7px;
    color: grey;
    font-size: 14px;
    border-bottom: 2px solid #4aa0b5;
    margin-bottom: 20px;
    width: fit-content;
  }

  .date {
    color: #808080;
  }

  .news_topic:not(:last-child) {
    /* padding-bottom: 5px; */
    border-bottom: solid 2px lightgray;
  }

  .news_report {
    font-weight: bold;
    font-size: 17px;
    color: black;
    margin-bottom: 5px;
  }

  .all-contents {
    padding: 15px;
    flex: 1;
  }

  .courses_contents {
    display: inline-block;
  }

  .event:not(:last-child) {
    padding-bottom: 10px;
    border-bottom: solid 2px lightgray;
  }

  .event {
    display: flex;
    padding: 10px 0;
  }

  .event_title {
    font-size: 17px;
    font-family: "Noto Selif JP", serif;
    font-weight: bold;
    color: black;
    margin: 0;
  }

  .event_post_contents {
    position: relative;
    color: #808080;
  }

  .event_contents {
    padding-left: 50px;
    flex: 6;
  }

  .calendar_box {
    display: inline-block;
    align-items: center;
    width: 100px;
    height: 100px;
    padding: 10px;
    background-color: #555555;
    color: #fff;
  }

  .calendar_box > .calendar_contents {
    border: 1px solid #fff;
  }

  .calendar_month {
    font-size: 12px;
    font-family: "Noto Selif JP", serif;
    text-align: center;
    padding-top: 4px;
  }

  .calendar_day {
    font-size: 40px;
    font-family: "Noto Selif JP", serif;
    text-align: center;
  }

  /* COURSE */

  #courses { 
    width: 100%;
    padding-top: 30px;
    padding-bottom: 60px;
  }

  .coures_image {
    max-width: 100%;
    border-radius: 10px 10px 0 0;
  }

  #all-contents2 {
    padding: 0px 5%;
  }

  .courses_1 {
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
  }

  .courses_2 {
    flex-basis: 0;
    flex-grow: 1;
    max-width: 100%;
  }

  .courses_title {
    max-width: 600px;
    width: fit-content;
    margin: 0 auto;
    color: black;
  }

  .top_title_sub2 {
    border-bottom: 2px solid #4aa0b5;
    line-height: 1.85;
    margin: 0 auto;
    width: fit-content;
  }

  .courses_contents {
    margin-top: 25px;
    display: block;
    /* margin-right: -15px; */
    /* margin-left: -15px; */
  }

  .course {
    /* flex: 3; */
    position: relative;
    margin: 20px 15px;
    /* margin-left: 15px; */
    width: 100%;
    background: #fff;
    box-sizing: 0px 1px 10px rgba(29, 34, 47, 0.1);
    box-shadow: 1px 2px 2px 1px lightgray;
    border-radius: 10px;
  }

  .course_title {
    height: 2.3em;
    padding: 0 20px;
    font-size: 22px;
  }

  .course_text {
    color: #808080;
    margin-top: 13px;
    height: 2.3em;
    font-size: 14px;
    padding: 0 20px;
  }

  .course_footer_content {
    width: 100%;
    padding: 20px 20px;
    text-align: end;
  }

  .course_footer_content_2 {
    color: #4aa0b5;
    font-size: 16px;
    font-weight: 700;
    margin-left: auto;
  }

  /* 数字 */

  .counter {
    width: 100%;
  }

  .counter_background {
    position: absolute;
    width: 100%;
  }

  .counter_1 {
    width: 100%;
    padding: 0px 5%;
  }

  .counter_2 {
    position: relative;
    box-sizing: border-box;
  }

  .counter_4 {
    padding-top: 20px;
    padding-bottom: 50px;
  }

  .counter_5 {
    margin-top: 40px;

  }

  .counter_7 {
    display: flex;
    justify-content: space-around;
    align-items: center;
    text-align: center;
    color: #fff;
  }

  .counter_contents {
    padding: 0 40px;
  }

  .counter_8 {
    display: flex;
  }

  .counter_8 .imag2 {
    width: 30%;
    height: 30%;
    object-fit: cover;
    position: relative;
    top: 5px;
    right: 5px;
  }

  .counter_8 .imag4 {
    width: 25%;
    height: 25%;
    object-fit: cover;
    position: relative;
    top: 5px;
    right: 5px;
  }

  .counter_8 .imag3 {
    width: 35%;
    height: 35%;
    object-fit: cover;
    position: relative;
    top: 5px;
    right: 5px;
  }

  .professor_counter {
    margin: 0; 
    font-size: 14px; 
    letter-spacing: 3px; 
    color: #fff;
  }

  .graduate_counter {
    margin: 0; 
    font-size: 14px; 
    letter-spacing: 3px; 
    color: #fff;
  }

  .learning_counter {
    margin: 0; 
    font-size: 14px; 
    letter-spacing: 3px; 
    color: #fff;
  }

  .award_counter {
    margin: 0; 
    font-size: 14px; 
    letter-spacing: 3px; 
    color: #fff;
  }



  .counters span {
    text-align: left;
    font-size: 40px;
    letter-spacing: 2px;
    opacity: 1;
  }

  .counters {
    margin: 0;
  }


  
  /* FOOTER */
  footer {
    display: block;
    position: relative;
    width: 100%;
    background-color: black;
    font-family: "Noto Selif JP", serif;
    padding-top: 60px;
    color: #fff;
  }

  .footer_1 {
    padding: 0 5%;
    display: flex;
  }

  .footer_right a {
    display: block;
    color: #fff;
  }

  .footer_2 {
    flex-grow: 1;
  }

  .footer_3 {
    padding-bottom: 50px;
  }

  .footer_4 {
    display: flex;
  }

  .area_logo_footer p {
    font-size: 20px;
  }

  .samurai_access {
    font-size: 15px;
    border-right: 1px solid #fff;
    padding-bottom: 5px;
    margin: 0;
  }

  .sns_footer {
    border-right: 1px solid #fff;
  }

  .sns_btns img {
    border-radius: 50%;
  } 

  .footer_center {
    margin-top: 85px;
    padding-top: 40px;
    padding-left: 60px;
    display: block;
  }

  .footer_center a {
    display: block;
    color: #b5b8be;
    font-size: 15px;
    margin-bottom: 5px;
  }

  .copy_right {
    background-color: #222222;
    padding: 5px 0;
  }

  .copy_right_text {
    color: #b5b8be;
    text-align: center;
    font-size: 12px;
  }

}
