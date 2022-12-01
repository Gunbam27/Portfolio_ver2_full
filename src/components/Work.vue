<template>
  <div className="wrap_work">
      <h2>Work</h2>
      <ul>
        <li>
          <a href="https://www.fsel.org/" target="_blank">
            <img
              src="https://gunbam27.github.io/Portfolio_ver2/img/work1.png"
              
              alt="한국영미문학페미니즘학회 사이트"
            />
            <!-- src="@/assets/img/work1.png" -->
            <div className="work_desc">
              <p className="bold">한국영미문학페미니즘학회</p>
              <p>22.10.25-11.02</p>
            </div>
          </a>
        </li>
        <li>
          <a href="https://www.fsel.org/" target="_blank">
            <img src="https://gunbam27.github.io/Portfolio_ver2/img/work2.png" alt="국어교육학회 사이트" />
            <div className="work_desc">
              <p className="bold">국어교육학회</p>
              <p>22.10.06-22.10.21</p>
            </div>
          </a>
        </li>
        <li>
          <a href="https://kiiedu.re.kr/" target="_blank">
            <img
              src="https://gunbam27.github.io/Portfolio_ver2/img/work3.png"
              alt="한국보험교육연구원 사이트"
            />
            <div className="work_desc">
              <p className="bold">한국보험교육연구원</p>
              <p>22.08.22-22.09.06</p>
            </div>
          </a>
        </li>
        <li>
          <a href="http://kswst.or.kr/" target="_blank">
            <img
              src="https://gunbam27.github.io/Portfolio_ver2/img/work4.png"
              alt="한국목재공학회 사이트"
            />
            <div className="work_desc">
              <p className="bold">한국목재공학회</p>
              <p>22.08.25-09.21</p>
            </div>
          </a>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  /* eslint-disable */
  export default {
      }
  </script>
  
  <style>
  
  .wrap_work ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap:2.5rem;
    padding: 0;
  }
  .wrap_work ul li {
    display: flex;
    flex-direction: column;
  
    /* margin: 20px;
    text-align: center; */
  }
  .wrap_work > ul > li a {
    text-decoration: none;
    color: black;
    /* font-weight: bold; */
    padding-top: 10px;
    font-size: 1rem;
  }

  .wrap_work ul li img {
    width: 300px;
    height: 250px;
    border-radius: 25px;
  }
  </style>