<html>
  <head>
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="" />
    <link
      rel="stylesheet"
      as="style"
      onload="this.rel='stylesheet'"
      href="https://fonts.googleapis.com/css2?display=swap&amp;family=Noto+Sans%3Awght%40400%3B500%3B700%3B900&amp;family=Space+Grotesk%3Awght%40400%3B500%3B700"
    />

    <title>Galileo Design</title>
    <link rel="icon" type="image/x-icon" href="data:image/x-icon;base64," />

    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  </head>
  <body>
    <div class="relative flex size-full min-h-screen flex-col bg-[#101a23] dark group/design-root overflow-x-hidden" style='font-family: "Space Grotesk", "Noto Sans", sans-serif;'>
      <div class="layout-container flex h-full grow flex-col">
        <header class="flex items-center justify-between whitespace-nowrap border-b border-solid border-b-[#223749] px-10 py-3">
          <div class="flex items-center gap-4 text-white">
            <div class="size-4">
              <svg viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M4 4H17.3334V17.3334H30.6666V30.6666H44V44H4V4Z" fill="currentColor"></path></svg>
            </div>
            <h2 class="text-white text-lg font-bold leading-tight tracking-[-0.015em]">3D Genie</h2>
          </div>
          <div class="flex flex-1 justify-end gap-8">
            <div class="flex items-center gap-9">
              <a class="text-white text-sm font-medium leading-normal" href="#">Home</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">Gallery</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">Docs</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">Run</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">Jobs</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">Notifications</a>
            </div>
            <div class="flex gap-2">
              <button
                class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 bg-[#2094f3] text-white text-sm font-bold leading-normal tracking-[0.015em]"
              >
                <span class="truncate">New</span>
              </button>
              <button
                class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 bg-[#223749] text-white gap-2 text-sm font-bold leading-normal tracking-[0.015em] min-w-0 px-2.5"
              >
                <div class="text-white" data-icon="MagnifyingGlass" data-size="20px" data-weight="regular">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor" viewBox="0 0 256 256">
                    <path
                      d="M229.66,218.34l-50.07-50.06a88.11,88.11,0,1,0-11.31,11.31l50.06,50.07a8,8,0,0,0,11.32-11.32ZM40,112a72,72,0,1,1,72,72A72.08,72.08,0,0,1,40,112Z"
                    ></path>
                  </svg>
                </div>
              </button>
              <button
                class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 bg-[#223749] text-white gap-2 text-sm font-bold leading-normal tracking-[0.015em] min-w-0 px-2.5"
              >
                <div class="text-white" data-icon="ChatDots" data-size="20px" data-weight="regular">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor" viewBox="0 0 256 256">
                    <path
                      d="M216,48H40A16,16,0,0,0,24,64V224a15.85,15.85,0,0,0,9.24,14.5A16.13,16.13,0,0,0,40,240a15.89,15.89,0,0,0,10.25-3.78.69.69,0,0,0,.13-.11L82.5,208H216a16,16,0,0,0,16-16V64A16,16,0,0,0,216,48ZM40,224h0ZM216,192H82.5a16,16,0,0,0-10.3,3.75l-.12.11L40,224V64H216ZM116,128a12,12,0,1,1,12,12A12,12,0,0,1,116,128Zm-44,0a12,12,0,1,1,12,12A12,12,0,0,1,72,128Zm88,0a12,12,0,1,1,12,12A12,12,0,0,1,160,128Z"
                    ></path>
                  </svg>
                </div>
              </button>
            </div>
          </div>
        </header>
        <div class="px-40 flex flex-1 justify-center py-5">
          <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
            <div class="flex flex-wrap justify-between gap-3 p-4"><p class="text-white tracking-light text-[32px] font-bold leading-tight min-w-72">Create a new job</p></div>
            <div class="flex flex-col gap-3 p-4">
              <div class="flex gap-6 justify-between"><p class="text-white text-base font-medium leading-normal">Step 1: Upload images</p></div>
              <div class="rounded bg-[#314f68]"><div class="h-2 rounded bg-[#2094f3]" style="width: 25%;"></div></div>
              <p class="text-[#90b0cb] text-sm font-normal leading-normal">1/4</p>
            </div>
            <p class="text-white text-base font-normal leading-normal pb-3 pt-1 px-4">Upload your 2D images to get started. We support .png and .jpeg formats</p>
            <div class="flex justify-stretch">
              <div class="flex flex-1 gap-3 flex-wrap px-4 py-3 justify-start">
                <button
                  class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 bg-[#223749] text-white text-sm font-bold leading-normal tracking-[0.015em]"
                >
                  <span class="truncate">Upload Images</span>
                </button>
                <button
                  class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 bg-[#2094f3] text-white text-sm font-bold leading-normal tracking-[0.015em]"
                >
                  <span class="truncate">Select Files</span>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

<html>
  <head>
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="" />
    <link
      rel="stylesheet"
      as="style"
      onload="this.rel='stylesheet'"
      href="https://fonts.googleapis.com/css2?display=swap&amp;family=Noto+Sans%3Awght%40400%3B500%3B700%3B900&amp;family=Space+Grotesk%3Awght%40400%3B500%3B700"
    />

    <title>Galileo Design</title>
    <link rel="icon" type="image/x-icon" href="data:image/x-icon;base64," />

    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  </head>
  <body>
    <div class="relative flex size-full min-h-screen flex-col bg-[#101a23] dark group/design-root overflow-x-hidden" style='font-family: "Space Grotesk", "Noto Sans", sans-serif;'>
      <div class="layout-container flex h-full grow flex-col">
        <header class="flex items-center justify-between whitespace-nowrap border-b border-solid border-b-[#223749] px-10 py-3">
          <div class="flex items-center gap-4 text-white">
            <div class="size-4">
              <svg viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M39.475 21.6262C40.358 21.4363 40.6863 21.5589 40.7581 21.5934C40.7876 21.655 40.8547 21.857 40.8082 22.3336C40.7408 23.0255 40.4502 24.0046 39.8572 25.2301C38.6799 27.6631 36.5085 30.6631 33.5858 33.5858C30.6631 36.5085 27.6632 38.6799 25.2301 39.8572C24.0046 40.4502 23.0255 40.7407 22.3336 40.8082C21.8571 40.8547 21.6551 40.7875 21.5934 40.7581C21.5589 40.6863 21.4363 40.358 21.6262 39.475C21.8562 38.4054 22.4689 36.9657 23.5038 35.2817C24.7575 33.2417 26.5497 30.9744 28.7621 28.762C30.9744 26.5497 33.2417 24.7574 35.2817 23.5037C36.9657 22.4689 38.4054 21.8562 39.475 21.6262ZM4.41189 29.2403L18.7597 43.5881C19.8813 44.7097 21.4027 44.9179 22.7217 44.7893C24.0585 44.659 25.5148 44.1631 26.9723 43.4579C29.9052 42.0387 33.2618 39.5667 36.4142 36.4142C39.5667 33.2618 42.0387 29.9052 43.4579 26.9723C44.1631 25.5148 44.659 24.0585 44.7893 22.7217C44.9179 21.4027 44.7097 19.8813 43.5881 18.7597L29.2403 4.41187C27.8527 3.02428 25.8765 3.02573 24.2861 3.36776C22.6081 3.72863 20.7334 4.58419 18.8396 5.74801C16.4978 7.18716 13.9881 9.18353 11.5858 11.5858C9.18354 13.988 7.18717 16.4978 5.74802 18.8396C4.58421 20.7334 3.72865 22.6081 3.36778 24.2861C3.02574 25.8765 3.02429 27.8527 4.41189 29.2403Z"
                  fill="currentColor"
                ></path>
              </svg>
            </div>
            <h2 class="text-white text-lg font-bold leading-tight tracking-[-0.015em]">3D Vision</h2>
          </div>
          <div class="flex flex-1 justify-end gap-8">
            <div class="flex items-center gap-9">
              <a class="text-white text-sm font-medium leading-normal" href="#">Home</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">Projects</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">Datasets</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">Models</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">API</a>
              <a class="text-white text-sm font-medium leading-normal" href="#">Docs</a>
            </div>
            <button
              class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 bg-[#223749] text-white gap-2 text-sm font-bold leading-normal tracking-[0.015em] min-w-0 px-2.5"
            >
              <div class="text-white" data-icon="Gear" data-size="20px" data-weight="regular">
                <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M128,80a48,48,0,1,0,48,48A48.05,48.05,0,0,0,128,80Zm0,80a32,32,0,1,1,32-32A32,32,0,0,1,128,160Zm88-29.84q.06-2.16,0-4.32l14.92-18.64a8,8,0,0,0,1.48-7.06,107.21,107.21,0,0,0-10.88-26.25,8,8,0,0,0-6-3.93l-23.72-2.64q-1.48-1.56-3-3L186,40.54a8,8,0,0,0-3.94-6,107.71,107.71,0,0,0-26.25-10.87,8,8,0,0,0-7.06,1.49L130.16,40Q128,40,125.84,40L107.2,25.11a8,8,0,0,0-7.06-1.48A107.6,107.6,0,0,0,73.89,34.51a8,8,0,0,0-3.93,6L67.32,64.27q-1.56,1.49-3,3L40.54,70a8,8,0,0,0-6,3.94,107.71,107.71,0,0,0-10.87,26.25,8,8,0,0,0,1.49,7.06L40,125.84Q40,128,40,130.16L25.11,148.8a8,8,0,0,0-1.48,7.06,107.21,107.21,0,0,0,10.88,26.25,8,8,0,0,0,6,3.93l23.72,2.64q1.49,1.56,3,3L70,215.46a8,8,0,0,0,3.94,6,107.71,107.71,0,0,0,26.25,10.87,8,8,0,0,0,7.06-1.49L125.84,216q2.16.06,4.32,0l18.64,14.92a8,8,0,0,0,7.06,1.48,107.21,107.21,0,0,0,26.25-10.88,8,8,0,0,0,3.93-6l2.64-23.72q1.56-1.48,3-3L215.46,186a8,8,0,0,0,6-3.94,107.71,107.71,0,0,0,10.87-26.25,8,8,0,0,0-1.49-7.06Zm-16.1-6.5a73.93,73.93,0,0,1,0,8.68,8,8,0,0,0,1.74,5.48l14.19,17.73a91.57,91.57,0,0,1-6.23,15L187,173.11a8,8,0,0,0-5.1,2.64,74.11,74.11,0,0,1-6.14,6.14,8,8,0,0,0-2.64,5.1l-2.51,22.58a91.32,91.32,0,0,1-15,6.23l-17.74-14.19a8,8,0,0,0-5-1.75h-.48a73.93,73.93,0,0,1-8.68,0,8,8,0,0,0-5.48,1.74L100.45,215.8a91.57,91.57,0,0,1-15-6.23L82.89,187a8,8,0,0,0-2.64-5.1,74.11,74.11,0,0,1-6.14-6.14,8,8,0,0,0-5.1-2.64L46.43,170.6a91.32,91.32,0,0,1-6.23-15l14.19-17.74a8,8,0,0,0,1.74-5.48,73.93,73.93,0,0,1,0-8.68,8,8,0,0,0-1.74-5.48L40.2,100.45a91.57,91.57,0,0,1,6.23-15L69,82.89a8,8,0,0,0,5.1-2.64,74.11,74.11,0,0,1,6.14-6.14A8,8,0,0,0,82.89,69L85.4,46.43a91.32,91.32,0,0,1,15-6.23l17.74,14.19a8,8,0,0,0,5.48,1.74,73.93,73.93,0,0,1,8.68,0,8,8,0,0,0,5.48-1.74L155.55,40.2a91.57,91.57,0,0,1,15,6.23L173.11,69a8,8,0,0,0,2.64,5.1,74.11,74.11,0,0,1,6.14,6.14,8,8,0,0,0,5.1,2.64l22.58,2.51a91.32,91.32,0,0,1,6.23,15l-14.19,17.74A8,8,0,0,0,199.87,123.66Z"
                  ></path>
                </svg>
              </div>
            </button>
            <div
              class="bg-center bg-no-repeat aspect-square bg-cover rounded-full size-10"
              style='background-image: url("https://cdn.usegalileo.ai/sdxl10/70f84e25-3810-4a06-873c-eb764904f18f.png");'
            ></div>
          </div>
        </header>
        <div class="gap-1 px-6 flex flex-1 justify-center py-5">
          <div class="layout-content-container flex flex-col w-80">
            <div class="flex h-full min-h-[700px] flex-col justify-between bg-[#101a23] p-4">
              <div class="flex flex-col gap-4">
                <div class="flex flex-col gap-2">
                  <div class="flex items-center gap-3 px-3 py-2"><p class="text-white text-sm font-medium leading-normal">Overview</p></div>
                  <div class="flex items-center gap-3 px-3 py-2 rounded-xl bg-[#223749]"><p class="text-white text-sm font-medium leading-normal">Optimization</p></div>
                  <div class="flex items-center gap-3 px-3 py-2"><p class="text-white text-sm font-medium leading-normal">Interpolation</p></div>
                  <div class="flex items-center gap-3 px-3 py-2"><p class="text-white text-sm font-medium leading-normal">Adjustment</p></div>
                  <div class="flex items-center gap-3 px-3 py-2"><p class="text-white text-sm font-medium leading-normal">Manual</p></div>
                </div>
              </div>
            </div>
          </div>
          <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
            <div class="flex flex-wrap justify-between gap-3 p-4"><p class="text-white tracking-light text-[32px] font-bold leading-tight min-w-72">Optimization</p></div>
            <div class="pb-3">
              <div class="flex border-b border-[#314f68] px-4 gap-8">
                <a class="flex flex-col items-center justify-center border-b-[3px] border-b-[#2094f3] text-white pb-[13px] pt-4" href="#">
                  <p class="text-white text-sm font-bold leading-normal tracking-[0.015em]">Point Cloud</p>
                </a>
                <a class="flex flex-col items-center justify-center border-b-[3px] border-b-transparent text-[#90b0cb] pb-[13px] pt-4" href="#">
                  <p class="text-[#90b0cb] text-sm font-bold leading-normal tracking-[0.015em]">Mesh</p>
                </a>
                <a class="flex flex-col items-center justify-center border-b-[3px] border-b-transparent text-[#90b0cb] pb-[13px] pt-4" href="#">
                  <p class="text-[#90b0cb] text-sm font-bold leading-normal tracking-[0.015em]">Texture</p>
                </a>
              </div>
            </div>
            <h3 class="text-white text-lg font-bold leading-tight tracking-[-0.015em] px-4 pb-2 pt-4">Noise Reduction</h3>
            <div class="@container">
              <div class="relative flex w-full flex-col items-start justify-between gap-3 p-4 @[480px]:flex-row">
                <p class="text-white text-base font-medium leading-normal w-full shrink-[3]">Noise Reduction</p>
                <div class="flex h-[38px] w-full pt-1.5">
                  <div class="flex h-1 w-full rounded-sm bg-[#314f68] pl-[60%] pr-[15%]">
                    <div class="relative">
                      <div class="absolute -left-3 -top-1.5 flex flex-col items-center gap-1">
                        <div class="size-4 rounded-full bg-[#2094f3]"></div>
                        <p class="text-white text-sm font-normal leading-normal">0</p>
                      </div>
                    </div>
                    <div class="h-1 flex-1 rounded-sm bg-[#2094f3]"></div>
                    <div class="relative">
                      <div class="absolute -left-3 -top-1.5 flex flex-col items-center gap-1">
                        <div class="size-4 rounded-full bg-[#2094f3]"></div>
                        <p class="text-white text-sm font-normal leading-normal">100</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <h3 class="text-white text-lg font-bold leading-tight tracking-[-0.015em] px-4 pb-2 pt-4">Accuracy Improvement</h3>
            <div class="@container">
              <div class="relative flex w-full flex-col items-start justify-between gap-3 p-4 @[480px]:flex-row">
                <p class="text-white text-base font-medium leading-normal w-full shrink-[3]">Accuracy Improvement</p>
                <div class="flex h-[38px] w-full pt-1.5">
                  <div class="flex h-1 w-full rounded-sm bg-[#314f68] pl-[60%] pr-[15%]">
                    <div class="relative">
                      <div class="absolute -left-3 -top-1.5 flex flex-col items-center gap-1">
                        <div class="size-4 rounded-full bg-[#2094f3]"></div>
                        <p class="text-white text-sm font-normal leading-normal">0</p>
                      </div>
                    </div>
                    <div class="h-1 flex-1 rounded-sm bg-[#2094f3]"></div>
                    <div class="relative">
                      <div class="absolute -left-3 -top-1.5 flex flex-col items-center gap-1">
                        <div class="size-4 rounded-full bg-[#2094f3]"></div>
                        <p class="text-white text-sm font-normal leading-normal">100</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="flex flex-col gap-3 p-4">
              <div class="flex gap-6 justify-between"><p class="text-white text-base font-medium leading-normal">Processing</p></div>
              <div class="rounded bg-[#314f68]"><div class="h-2 rounded bg-[#2094f3]" style="width: 80%;"></div></div>
              <p class="text-[#90b0cb] text-sm font-normal leading-normal">This may take a few minutes</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

<html>
  <head>
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="" />
    <link
      rel="stylesheet"
      as="style"
      onload="this.rel='stylesheet'"
      href="https://fonts.googleapis.com/css2?display=swap&amp;family=Noto+Sans%3Awght%40400%3B500%3B700%3B900&amp;family=Space+Grotesk%3Awght%40400%3B500%3B700"
    />

    <title>Galileo Design</title>
    <link rel="icon" type="image/x-icon" href="data:image/x-icon;base64," />

    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  </head>
  <body>
    <div
      class="relative flex size-full min-h-screen flex-col bg-[#101a23] dark group/design-root overflow-x-hidden"
      style='--radio-dot-svg: url(&apos;data:image/svg+xml,%3csvg viewBox=%270 0 16 16%27 fill=%27rgb(32,148,243)%27 xmlns=%27http://www.w3.org/2000/svg%27%3e%3ccircle cx=%278%27 cy=%278%27 r=%273%27/%3e%3c/svg%3e&apos;); font-family: "Space Grotesk", "Noto Sans", sans-serif;'
    >
      <div class="layout-container flex h-full grow flex-col">
        <div class="gap-1 px-6 flex flex-1 justify-center py-5">
          <div class="layout-content-container flex flex-col w-80">
            <div class="flex h-full min-h-[700px] flex-col justify-between bg-[#101a23] p-4">
              <div class="flex flex-col gap-4">
                <h1 class="text-white text-base font-medium leading-normal">Model: 3D scan of a box</h1>
                <div class="flex flex-col gap-2">
                  <div class="flex items-center gap-3 px-3 py-2"><p class="text-white text-sm font-medium leading-normal">Overview</p></div>
                  <div class="flex items-center gap-3 px-3 py-2"><p class="text-white text-sm font-medium leading-normal">Reports</p></div>
                  <div class="flex items-center gap-3 px-3 py-2 rounded-xl bg-[#223749]"><p class="text-white text-sm font-medium leading-normal">Export</p></div>
                </div>
              </div>
              <div class="flex flex-col gap-1">
                <div class="flex items-center gap-3 px-3 py-2">
                  <div class="text-white" data-icon="Book" data-size="24px" data-weight="regular">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                      <path
                        d="M208,24H72A32,32,0,0,0,40,56V224a8,8,0,0,0,8,8H192a8,8,0,0,0,0-16H56a16,16,0,0,1,16-16H208a8,8,0,0,0,8-8V32A8,8,0,0,0,208,24Zm-8,160H72a31.82,31.82,0,0,0-16,4.29V56A16,16,0,0,1,72,40H200Z"
                      ></path>
                    </svg>
                  </div>
                  <p class="text-white text-sm font-medium leading-normal">Documentation</p>
                </div>
                <div class="flex items-center gap-3 px-3 py-2">
                  <div class="text-white" data-icon="Question" data-size="24px" data-weight="regular">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                      <path
                        d="M140,180a12,12,0,1,1-12-12A12,12,0,0,1,140,180ZM128,72c-22.06,0-40,16.15-40,36v4a8,8,0,0,0,16,0v-4c0-11,10.77-20,24-20s24,9,24,20-10.77,20-24,20a8,8,0,0,0-8,8v8a8,8,0,0,0,16,0v-.72c18.24-3.35,32-17.9,32-35.28C168,88.15,150.06,72,128,72Zm104,56A104,104,0,1,1,128,24,104.11,104.11,0,0,1,232,128Zm-16,0a88,88,0,1,0-88,88A88.1,88.1,0,0,0,216,128Z"
                      ></path>
                    </svg>
                  </div>
                  <p class="text-white text-sm font-medium leading-normal">Help &amp; feedback</p>
                </div>
              </div>
            </div>
          </div>
          <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
            <div class="flex flex-wrap justify-between gap-3 p-4"><p class="text-white tracking-light text-[32px] font-bold leading-tight min-w-72">Export</p></div>
            <div class="pb-3">
              <div class="flex border-b border-[#314f68] px-4 gap-8">
                <a class="flex flex-col items-center justify-center border-b-[3px] border-b-[#2094f3] text-white pb-[13px] pt-4" href="#">
                  <p class="text-white text-sm font-bold leading-normal tracking-[0.015em]">Preview</p>
                </a>
                <a class="flex flex-col items-center justify-center border-b-[3px] border-b-transparent text-[#90b0cb] pb-[13px] pt-4" href="#">
                  <p class="text-[#90b0cb] text-sm font-bold leading-normal tracking-[0.015em]">Point cloud</p>
                </a>
                <a class="flex flex-col items-center justify-center border-b-[3px] border-b-transparent text-[#90b0cb] pb-[13px] pt-4" href="#">
                  <p class="text-[#90b0cb] text-sm font-bold leading-normal tracking-[0.015em]">Mesh</p>
                </a>
                <a class="flex flex-col items-center justify-center border-b-[3px] border-b-transparent text-[#90b0cb] pb-[13px] pt-4" href="#">
                  <p class="text-[#90b0cb] text-sm font-bold leading-normal tracking-[0.015em]">Texture</p>
                </a>
                <a class="flex flex-col items-center justify-center border-b-[3px] border-b-transparent text-[#90b0cb] pb-[13px] pt-4" href="#">
                  <p class="text-[#90b0cb] text-sm font-bold leading-normal tracking-[0.015em]">Normals</p>
                </a>
              </div>
            </div>
            <h2 class="text-white text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5">Preview</h2>
            <div class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3 p-4">
              <div class="flex flex-col gap-3 text-center">
                <div class="px-4">
                  <div
                    class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-full"
                    style='background-image: url("https://cdn.usegalileo.ai/sdxl10/b5653078-a6fe-4e13-b661-2d9c52f3415c.png");'
                  ></div>
                </div>
              </div>
              <div class="flex flex-col gap-3 text-center">
                <div class="px-4">
                  <div
                    class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-full"
                    style='background-image: url("https://cdn.usegalileo.ai/sdxl10/c52f59e1-59c0-498b-b0da-1a5fd8bfd3df.png");'
                  ></div>
                </div>
              </div>
              <div class="flex flex-col gap-3 text-center">
                <div class="px-4">
                  <div
                    class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-full"
                    style='background-image: url("https://cdn.usegalileo.ai/sdxl10/9152518c-c5f8-48ee-9d82-e77dd6cfdba4.png");'
                  ></div>
                </div>
              </div>
              <div class="flex flex-col gap-3 text-center">
                <div class="px-4">
                  <div
                    class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-full"
                    style='background-image: url("https://cdn.usegalileo.ai/sdxl10/b9fe5eac-b468-4bb8-b127-f5f15e98af44.png");'
                  ></div>
                </div>
              </div>
            </div>
            <h2 class="text-white text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5">Point cloud</h2>
            <div class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3 p-4">
              <div class="flex flex-col gap-3 text-center">
                <div class="px-4">
                  <div
                    class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-full"
                    style='background-image: url("https://cdn.usegalileo.ai/sdxl10/856b095a-4902-4fc1-8483-f6714a9c4718.png");'
                  ></div>
                </div>
              </div>
              <div class="flex flex-col gap-3 text-center">
                <div class="px-4">
                  <div
                    class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-full"
                    style='background-image: url("https://cdn.usegalileo.ai/sdxl10/0e4816da-70bc-4520-bb4d-63881875d151.png");'
                  ></div>
                </div>
              </div>
              <div class="flex flex-col gap-3 text-center">
                <div class="px-4">
                  <div
                    class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-full"
                    style='background-image: url("https://cdn.usegalileo.ai/sdxl10/3d383dfd-ec1b-46ba-af72-0eeb305ec01b.png");'
                  ></div>
                </div>
              </div>
              <div class="flex flex-col gap-3 text-center">
                <div class="px-4">
                  <div
                    class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-full"
                    style='background-image: url("https://cdn.usegalileo.ai/sdxl10/cfad0eb3-8e94-4b2d-9605-347331c47822.png");'
                  ></div>
                </div>
              </div>
            </div>
            <div class="flex px-4 py-3">
              <button
                class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 flex-1 bg-[#223749] text-white text-sm font-bold leading-normal tracking-[0.015em]"
              >
                <span class="truncate">Download point cloud</span>
              </button>
            </div>
            <h2 class="text-white text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5">Export options</h2>
            <div class="flex flex-col gap-3 p-4">
              <label class="flex items-center gap-4 rounded-xl border border-solid border-[#314f68] p-[15px]">
                <input
                  type="radio"
                  class="h-5 w-5 border-2 border-[#314f68] bg-transparent text-transparent checked:border-[#2094f3] checked:bg-[image:--radio-dot-svg] focus:outline-none focus:ring-0 focus:ring-offset-0 checked:focus:border-[#2094f3]"
                  name="89d4915a-40dd-493d-84f9-acdc6fec0406"
                  checked=""
                />
                <div class="flex grow flex-col"><p class="text-white text-sm font-medium leading-normal">OBJ</p></div>
              </label>
              <label class="flex items-center gap-4 rounded-xl border border-solid border-[#314f68] p-[15px]">
                <input
                  type="radio"
                  class="h-5 w-5 border-2 border-[#314f68] bg-transparent text-transparent checked:border-[#2094f3] checked:bg-[image:--radio-dot-svg] focus:outline-none focus:ring-0 focus:ring-offset-0 checked:focus:border-[#2094f3]"
                  name="89d4915a-40dd-493d-84f9-acdc6fec0406"
                />
                <div class="flex grow flex-col"><p class="text-white text-sm font-medium leading-normal">GLTF</p></div>
              </label>
              <label class="flex items-center gap-4 rounded-xl border border-solid border-[#314f68] p-[15px]">
                <input
                  type="radio"
                  class="h-5 w-5 border-2 border-[#314f68] bg-transparent text-transparent checked:border-[#2094f3] checked:bg-[image:--radio-dot-svg] focus:outline-none focus:ring-0 focus:ring-offset-0 checked:focus:border-[#2094f3]"
                  name="89d4915a-40dd-493d-84f9-acdc6fec0406"
                />
                <div class="flex grow flex-col"><p class="text-white text-sm font-medium leading-normal">STL</p></div>
              </label>
            </div>
            <div class="flex px-4 py-3">
              <button
                class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 flex-1 bg-[#2094f3] text-white text-sm font-bold leading-normal tracking-[0.015em]"
              >
                <span class="truncate">Export</span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>