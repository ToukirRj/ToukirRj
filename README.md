<div className='relative z-20'>
                <div className="md:pt-[180px] pt-[110px] pb-12 relative z-10">
                    <div className="mx-auto px-4 md:px-12 xl:max-w-7xl xl:px-0">
                        <div className=" flex md:flex-row flex-col items-center justify-center gap-3 relative z-20 ">
                            <div className="min-h-[422px] h-auto md:w-2/5 w-full relative rounded-[60px] p-[40px] bg-white/[0.2] dark:bg-white/[.05] dark:border-0 border border-white/[0.15]" data-aos="fade-up" data-aos-duration="300" data-aos-delay="100">
                                <img className="w-[180px] max-w-full mx-auto" src={Selfsign} alt="me" data-aos="fade-up" data-aos-duration="300" data-aos-delay="100"/>
                                <h1 className="my-2 md:text-[43px] text-[32px] font-[700] text-[#1f2937] dark:text-white tracking-tight md:leading-[55px] leading-[45px] w-full text-center" data-aos="fade-up" data-aos-duration="300" data-aos-delay="100">
                                    Toukir Rahman
                                </h1>
                                <div className="mt-2 border-t border-[#1F2937]/[0.12] pt-4 relative z-10" data-aos="fade-up" data-aos-duration="300" data-aos-delay="100">
                                    <div className="flex justify-center">
                                        <Link className="group h-[46px] w-auto relative overflow-hidden z-10 flex items-center rounded-full ps-4 pe-[12px] bg-[#20bd62] hover:bg-[#299c59] ease-in-out duration-500" to="https://wa.me/8801753778070" target="_blank">
                                            <span className="w-[38px] h-[38px] absolute -z-[1] left-[5px] bg-[#2b6e58] group-hover:bg-[#235847] rounded-full btn-left ease-in-out duration-500"></span>
                                            <span className="text-[#fff] text-[14px] font-[400] tracking-[0.5px]">WhatsApp</span>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 1024 1024" className='relative ms-[12px]'>
                                                <path fill="#fff" d="M768 256H353.6a32 32 0 1 1 0-64H800a32 32 0 0 1 32 32v448a32 32 0 0 1-64 0z"/>
                                                <path fill="#fff" d="M777.344 201.344a32 32 0 0 1 45.312 45.312l-544 544a32 32 0 0 1-45.312-45.312z"/>
                                            </svg>
                                        </Link>       
                                    </div>
                                </div>
                            </div>
                            <div className="min-h-[422px] h-auto md:w-3/5 w-full rounded-[60px] sm:block flex flex-col items-center pt-[50px] md:p-[45px] p-5 z-10 md:mt-0 mt-6 bg-white/[0.2] dark:bg-white/[.05] dark:border-0 border border-white/[0.15]" data-aos="fade-up" data-aos-duration="300" data-aos-delay="100">
                                <h4 className="bg-[#1F2937] dark:bg-white/[.1] text-[#fff] text-[13px] font-[400] tracking-wider px-4 py-1 rounded-full table md:mx-0 mx-auto" data-aos="fade-up" data-aos-duration="300" data-aos-delay="100">Front-End Engineer | UX/UI Engineer</h4>
                                <h1 className="md:my-[23px] my-[17px] text-[#1f2937] dark:text-white md:text-[55px] text-[25px] font-[700] md:leading-[64px] leading-[36px] tracking-normal md:text-start text-center" data-aos="fade-up" data-aos-duration="300" data-aos-delay="150">
                                    Addicted to Advanced<span className='bg-gradient-to-r from-[#ff8144] to-[#17b057] inline-block text-transparent bg-clip-text'>Design and Coding</span></h1>
                                <p className="md:text-[15px] text-[13px] leading-[30px] font-[400] tracking-[0.35px] text-[#1F2937] dark:text-white/[0.8] md:text-start text-center" data-aos="fade-up" data-aos-duration="300" data-aos-delay="200">
                                    A safe hand to take your vision & the weight of your project off your shoulders, to getting done 
                                    perfectly. A Professional Website Application Engineer with a passion for creating inspiring and influential designs. Committed to working with honesty and dedication.
                                </p>
                            </div>
                        </div>
                        <div className='mt-3 flex justify-center' data-aos="fade-up" data-aos-duration="300" data-aos-delay="300">
                            <div className='p-2 md:w-auto w-full rounded-[40px] bg-white/[.2] border border-white/[0.25] dark:bg-white/[.05] dark:border-0'>
                                {/* <h1 className="text-[21px] font-semibold tracking-tight text-[#1f2937] my-3 text-center" data-aos="fade-up" data-aos-duration="300" data-aos-delay="200">Get Me Connect Now on</h1> */}
                                <div className="flex md:flex-row flex-col items-center justify-center gap-2 mx-auto">
                                    {socialLinksData.map(link => (
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
                                    ))}
                                </div>
                            </div>
                        </div>
                        <div className="mt-24 relative z-10 md:block hidden">
                            <div className="flex justify-center">
                                <a href="#about" className='table'>
                                    <svg className="mouse" width="40px" viewBox="0 0 247 390" xmlns="http://www.w3.org/2000/svg">
                                        <path id="wheel" d="M123.359,79.775l0,72.843" fill="none" stroke="#1F2937" strokeWidth="10px"/>
                                        <path id="mouse" d="M236.717,123.359c0,-62.565 -50.794,-113.359 -113.358,-113.359c-62.565,0 -113.359,50.794 -113.359,113.359l0,143.237c0,62.565 50.794,113.359 113.359,113.359c62.564,0 113.358,-50.794 113.358,-113.359l0,-143.237Z" fill="none" stroke="#1F2937" strokeWidth="10px" />
                                    </svg>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
