
<div className="min-h-[422px] h-auto md:w-2/5 w-full relative rounded-[60px] p-[40px] bg-white/[0.2] dark:bg-white/[.05] dark:border-0 border border-white/[0.15]" data-aos="fade-up" data-aos-duration="300" data-aos-delay="100">
    <h4>Hey, Expert Minds! 👋</h4>
    <h1 className="my-2 md:text-[43px] text-[32px] font-[700] text-[#1f2937] dark:text-white tracking-tight md:leading-[55px] leading-[45px] w-full text-center" data-aos="fade-up" data-aos-duration="300" data-aos-delay="100">
        Here I'm Toukir Rahman!
    </h1>
    <h1 className="md:my-[23px] my-[17px] text-[#1f2937] dark:text-white md:text-[55px] text-[25px] font-[700] md:leading-[64px] leading-[36px] tracking-normal md:text-start text-center" data-aos="fade-up" data-aos-duration="300" data-aos-delay="150">
        Addicted to Advanced<span className='bg-gradient-to-r from-[#ff8144] to-[#17b057] inline-block text-transparent bg-clip-text'>Design and Coding</span>
    </h1>
    <p className="md:text-[15px] text-[13px] leading-[30px] font-[400] tracking-[0.35px] text-[#1F2937] dark:text-white/[0.8] md:text-start text-center" data-aos="fade-up" data-aos-duration="300" data-aos-delay="200">
        A safe hand to take your vision & the weight of your project off your shoulders, to get done perfectly. A Professional Website Application Engineer with a passion for creating inspiring and influential designs. Committed to working with honesty and dedication.
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
