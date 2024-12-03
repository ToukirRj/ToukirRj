
<div style="display:flex;align-items:center;flex-direction:column">
    <h4>Hey, Expert Minds! 👋</h4>
    <h1> Here I'm Toukir Rahman!</h1>
    <h3>Addicted to Advanced Design and Coding</span></h3>
    <p>
        A safe hand to take your vision & the weight of your project off your shoulders, to get that done perfectly. A Professional Website Application Engineer & UX/UI Designer with a passion for 
        creating inspiring and influential designs. Committed to working with honesty and dedication.
    </p>
</div>




<div className='mt-3 flex justify-center' data-aos="fade-up" data-aos-duration="300" data-aos-delay="300">
  <Link key={link.id} to={link.url} target={link.target}
      className="px-2 md:w-auto w-full h-[58px] flex items-center md:justify-center justify-between bg-white/[0.35] hover:bg-white/[0.75] dark:bg-white/[.05] dark:border-0 dark:hover:bg-white/[0.15] rounded-[70px] hover:shadow-lg transition-all border border-white/[0.25]" data-aos="fade-up" data-aos-duration="300" data-aos-delay="300">
      <div className='flex items-center'>
          <img className="w-6 h-6 rounded-full ms-3 md:me-1 me-3" src={link.imageSrc} alt={`${link.platform} logo`} />
          <p className="md:text-[14px] text-[15px] font-[500] text-[#1f2937] dark:text-white tracking-[.45px] me-3">{link.platform}</p>
      </div>
      <span className='h-11 w-11 flex items-center justify-center bg-transparent rounded-full border border-[#1f2937]/[0.13] dark:border-0 dark:bg-white/[.15]'>
          <svg xmlns="http://www.w3.org/2000/svg" width="21" height="21" viewBox="0 0 1024 1024" className='relative'>
              <path className='dark:fill-white' fill="#1f2937" d="M768 256H353.6a32 32 0 1 1 0-64H800a32 32 0 0 1 32 32v448a32 32 0 0 1-64 0z"/>
              <path className='dark:fill-white' fill="#1f2937" d="M777.344 201.344a32 32 0 0 1 45.312 45.312l-544 544a32 32 0 0 1-45.312-45.312z"/>
          </svg>
      </span>
  </Link>
</div>
