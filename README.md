#stylesheet


.headline{
  position: absolute;
  background: #009688;
  color:#fff;
  font-size: 27px;
  font-family: sans-serif;
  z-index: 9999;
  padding: 9px 25px 8px 15px;
}
.news-areas{
  width: 100%;
  overflow: hidden;
  
}
.tickers{
  width: 100%;
  padding-left: 0;
  background: #2a8853;
}
.ticker-animations{
  display:flex;
  white-space: nowrap;
  padding-right: 100%;
  animation: ticker 20s linear infinite;
}
.ticker-animations:hover{
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
.ticker-items{
 
  padding:10px 0;
  font-size: 25px;
  color: black ;
}


#code




 <>
        <div className='headline'>International</div>
        <div className='news-areas'>
          <div className='tickers'>
            <div className='ticker-animations'>

             <div className='ticker-items'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>

             <div className='ticker-items'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>

             <div className='ticker-items'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>

             <div className='ticker-items'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>

             <div className='ticker-items'> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <span>||</span></div>
            
            </div>
          </div>
        </div>
        </>
