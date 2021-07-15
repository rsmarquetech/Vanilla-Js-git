# Vanilla-Js-git/

*============== TOGGLE MENU SHOW ==============*/ 
    const navMenu = document.querySelector('.navbar-items'),
        toggleMenu = document.querySelector('.navToggle'),
        navClose = document.querySelector('.navClose')
         
          toggleMenu.addEventListener('click', () =>{
              navMenu.classList.toggle('showMenu')
          }); 

        if(navClose){
          navClose.addEventListener('click', () =>{
              navMenu.classList.remove('showMenu');
          });
        }; 
      
      
 /*==================== REMOVE NAVMENU ON LINK ACTION ====================*/
      const navItem = document.querySelectorAll('.nav-item') 
       
      navItem.forEach(n => n.addEventListener('click', ()=>{
        const navMenu = document.getElementById('navbarItems') 
        navMenu.classList.remove('showMenu')
      }))



/*==================== CHANGE HEADER/NAVBAR BACKGROUND ====================*/ 
    window.addEventListener('scroll', ()=>{

      // IT WILL CHANGE HEAHER BACKGROUND WHEN SCROLL PAGE IS EQUAL OR LESS THAN 100vh

      const navbar = document.getElementById('navbar')  
      if(this.scrollY >= 100) 
      {
        navbar.classList.add('scroll-navbar');
      } 
 
      else 
      {
        navbar.classList.remove('scroll-navbar')
      }
    }) 
    
    /*==================== SHOW SCROLL UP ====================*/  
    window.addEventListener('scroll', ()=>{
      // It will show scrll button when scroll page is high from 200vh 
      const scrollUp = document.getElementById('scroll-up'); 
      if(this.scrollY >= 200) scrollUp.classList.add('show-scroll'); else scrollUp.classList.remove('show-scroll')
    })
