#stylesheet


.news-area{
  width: 100%;
  overflow: hidden;
  
}
.tickers{
  width: 100%;
  background: #3b3b3b3d;
}
.ticker-animation{
  display:flex;
  white-space: nowrap;
  padding-right: 100%;
  animation: ticker 20s linear infinite;
}
.ticker-animation:hover{
 animation-play-state: paused;
}
@keyframes ticker{
  0%{
    transform: translate3d(0,0,0);
  }
  100%{
    transform: translate3d(-100%,0,0);
  }
}
.ticker-item{
 
  padding:5px 2px;
  font-size: 15px;
  color: rgb(255, 255, 255) ;
}



#code




<div className='headline'>International</div>
        <div className='news-area'>
          <div className='tickers'>
            <div className='ticker-animation'>

             <div className='ticker-item'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>

             <div className='ticker-item'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>

             <div className='ticker-item'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>

             <div className='ticker-item'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>

             <div className='ticker-item'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>
            
            </div>
          </div>
        </div>
