<script>
    import idstudioLogo from "/src/lib/images/Idstudio_logo.svg";
    import upArrow from "/src/lib/images/up-arrow.svg";
    let anchorStyle = "{text-[#292929] font-inter-tight text-[12px] font-light leading-[14.4px] lg:text-[18px] lg:leading-[28px] lg:font-light}";
</script>

<style>
.custom-text-stroke {
  -webkit-text-stroke-width: 1px; /* Default for mobile */
  -webkit-text-stroke-color: rgba(17, 17, 17, 0.20);
  color: rgba(17, 17, 17, 0);
}

/* For larger screens like laptop */
@media (min-width: 1024px) {
  .custom-text-stroke {
    -webkit-text-stroke-width: 3px;
  }
}

</style>


<footer class="flex max-w-[428px] px-4 pt-6 pb-0 justify-center rounded-t-[30px] rounded-b-none bg-[#F3F0EB] sm:rounded-t-none sm:max-w-full sm:px-20 sm:pt-10 sm:pb-0 sm:self-stretch overflow-hidden">
    <div class="flex w-full max-w-[396px] flex-col items-center gap-6 flex-shrink-0 sm:w-full sm:max-w-[1280px] sm:gap-10">
        <!-- FOOTER CONTENT -->
        <div class="flex flex-col items-center gap-6 self-stretch sm:items-start sm:gap-10">
            <!-- FOOTER TITLE SECTION -->
            <div class="flex justify-between items-center self-stretch">
                <!-- LOGO -->
                <a href="/">
                    <div class="w-[116px] h-[24px] sm:w-[126.61px] sm:h-[28px]">
                      <img src={idstudioLogo} alt="Logo" class="w-40" />
                    </div>
                </a>
    
                <!-- BACK TO TOP -->
                <a href="/">
                    <div class="flex items-center gap-1.5 sm:gap-2">
                        <div class="text-[#292929] font-inter-tight text-[14px] font-medium leading-[19.6px] sm:text-[24px] sm:leading-[33.6px] sm:text-[#111]">
                            BACK TO TOP
                        </div>
                        <div class="w-[24px] h-[24px]">
                            <img src={upArrow} alt="Up Arrow" class="w-24" />
                        </div>  
                    </div>
                </a>
            </div>
    
            <!-- FOOTER ANCHOR TAGS -->
            <div class="flex flex-col items-center gap-6 self-stretch sm:flex-row sm:justify-between sm:items-center sm:gap-0">
                <div class="flex items-center gap-5">
                    <a href="/" class="{anchorStyle}">How it works</a>
                    <a href="/" class="{anchorStyle}">Our Services</a>
                    <a href="/" class="{anchorStyle}">Portfolio</a>
                    <a href="/" class="{anchorStyle}">FAQs</a>
                    <a href="/" class="{anchorStyle}">Invisible Grills</a>
                </div>
                <div class="flex items-start gap-4 sm:gap-8">
                    <a href="/" class="{anchorStyle}">Terms of Use</a>
                    <a href="/" class="{anchorStyle}">Privacy Policy</a>
                    <a href="/" class="{anchorStyle}">Contact Us</a>
                </div>
            </div>
        </div>

        <!-- FOOTER INDUS STUDIO-->
        <div class="flex justify-center items-center self-stretch">
            <p class="inline-block text-center font-playfairDisplay text-[48px] font-semibold uppercase custom-text-stroke sm:text-[70px] md:text-[108px] lg:text-[118px] xl:text-[154px] leading-[90%] m-0">
              INDUS STUDIO
            </p>
          </div>
                   
    </div>
</footer>