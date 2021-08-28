<template>
  <div>
<div class="c-menu">

<ul class="c-menu__ul">

  <li v-on:click="getAllList()" class="c-menu__li">
  <svg class="c-icone" id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><title>filled-globe-glyph</title><path d="M127.61,248.24H247.38V158.65H144.83a282.69,282.69,0,0,0-17.22,89.59Z" fill="#231f20"/><path d="M125.31,158.65H20.12A253.75,253.75,0,0,0,1.82,248.24H109.24a301.75,301.75,0,0,1,16.06-89.59Z" fill="#231f20"/><path d="M152.27,140.3h95.11V15.11c-22.33,18.06-67,62-95.11,125.19Z" fill="#231f20"/><path d="M179.94,59.45A357.88,357.88,0,0,1,239.61,0C146.95,5.88,67.77,61.4,28.38,140.3H132.21a336.18,336.18,0,0,1,47.73-80.85Z" fill="#231f20"/><path d="M384.39,248.24H264.63V158.65H367.18a281.71,281.71,0,0,1,17.22,89.59Z" fill="#231f20"/><path d="M386.7,158.65H491.89a253.89,253.89,0,0,1,18.3,89.59H402.77a301.65,301.65,0,0,0-16.08-89.59Z" fill="#231f20"/><path d="M359.75,140.3H264.63V15.11c22.32,18.06,67.05,62,95.12,125.19Z" fill="#231f20"/><path d="M332.06,59.45A357,357,0,0,0,272.41,0c92.66,5.88,171.84,61.4,211.2,140.3H379.81a336.47,336.47,0,0,0-47.75-80.85Z" fill="#231f20"/><path d="M127.61,263.75H247.38v89.6H144.83a282.67,282.67,0,0,1-17.22-89.6Z" fill="#231f20"/><path d="M125.31,353.35H20.12a253.82,253.82,0,0,1-18.31-89.6H109.24a301.7,301.7,0,0,0,16.06,89.6Z" fill="#231f20"/><path d="M152.27,371.69h95.11V496.88c-22.33-18-67-62-95.11-125.18Z" fill="#231f20"/><path d="M179.94,452.56A358.07,358.07,0,0,0,239.61,512c-92.66-5.87-171.83-61.42-211.22-140.31H132.21a336.71,336.71,0,0,0,47.73,80.87Z" fill="#231f20"/><path d="M384.39,263.75H264.63v89.6H367.18a281.69,281.69,0,0,0,17.22-89.6Z" fill="#231f20"/><path d="M386.7,353.35H491.89a254,254,0,0,0,18.3-89.6H402.77a301.61,301.61,0,0,1-16.08,89.6Z" fill="#231f20"/><path d="M359.75,371.69H264.63V496.88c22.32-18,67.05-62,95.12-125.18Z" fill="#231f20"/><path d="M332.06,452.56A357.24,357.24,0,0,1,272.41,512c92.66-5.87,171.84-61.42,211.2-140.31H379.81a337,337,0,0,1-47.75,80.87Z" fill="#231f20"/></svg>
    Todos </li>
  

  <li v-on:click="getProfissionais()" class="c-menu__li">
  <svg class="c-icone" id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 512"><defs><linearGradient id="linear-gradient" x1="256" y1="491.29" x2="256" y2="20.71" gradientUnits="userSpaceOnUse"><stop offset="0" stop-color="#231f20"/><stop offset="1" stop-color="#58595b"/></linearGradient></defs><title>briefcase</title><path d="M512,229.15V465.68a25.68,25.68,0,0,1-25.61,25.61H25.59A25.66,25.66,0,0,1,0,465.68V229.15H230.5V293.7h51V229.15ZM0,205.2V149.39a25.68,25.68,0,0,1,25.59-25.61H152.91V58a37.37,37.37,0,0,1,37.32-37.31H321.75A37.37,37.37,0,0,1,359.07,58v65.76H486.39A25.7,25.7,0,0,1,512,149.39V205.2H281.48V185.46h-51V205.2Zm186.71-81.42H325.28V58a3.54,3.54,0,0,0-3.53-3.53H190.23A3.54,3.54,0,0,0,186.71,58Z" fill-rule="evenodd" fill="url(#linear-gradient)"/></svg>
   Profissional</li>

  <li v-on:click="getReguladores()" class="c-menu__li">
  <svg class="c-icone"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><defs><!-- <style>.cls-1{fill:#141f38;}</style> --></defs><title>bank-glyph</title><path class="cls-1" d="M166.41,243.21v128a12.8,12.8,0,0,1,12.8,12.8v25.6h-128V384A12.8,12.8,0,0,1,64,371.2v-128a12.8,12.8,0,0,1-12.8-12.8v-25.6h128v25.6A12.8,12.8,0,0,1,166.41,243.21Zm294.38-12.8v-25.6h-128v25.6a12.8,12.8,0,0,0,12.8,12.8v128a12.8,12.8,0,0,0-12.8,12.8v25.6h128V384A12.8,12.8,0,0,0,448,371.2v-128A12.8,12.8,0,0,0,460.78,230.41ZM1.1,154.76c-3.83-15,2.55-29.93,15.87-37.22L210.32,11.74a94.76,94.76,0,0,1,91.36,0L495,117.53c13.32,7.29,19.7,22.25,15.87,37.22-3.74,14.62-16.18,24.45-31,24.45H32.06C17.28,179.21,4.84,169.38,1.1,154.76ZM217.6,89.61A38.4,38.4,0,1,0,256,51.21,38.4,38.4,0,0,0,217.6,89.61ZM448,435.2H64a64.07,64.07,0,0,0-64,64V512H512V499.2A64.07,64.07,0,0,0,448,435.2ZM320,230.41v-25.6H192v25.6a12.8,12.8,0,0,0,12.8,12.8v128A12.8,12.8,0,0,0,192,384v25.6H320V384a12.8,12.8,0,0,0-12.8-12.8v-128A12.8,12.8,0,0,0,320,230.41Z"/></svg>
  Reguladores</li>

  <li v-on:click="getSocioAmbiental()" class="c-menu__li">
  <svg class="c-icone" id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><title>tree-glyph</title><path d="M37.33,500.32A10.67,10.67,0,0,1,26.67,511h-16a10.67,10.67,0,0,1,0-21.33h16A10.67,10.67,0,0,1,37.33,500.32Zm464-10.67h-16a10.67,10.67,0,0,0,0,21.33h16a10.67,10.67,0,1,0,0-21.33ZM96,489.65H64A10.67,10.67,0,0,0,64,511H96a10.67,10.67,0,0,0,0-21.33ZM205.44,217.76c26.39,3.81,45,9.43,60,14C286.26,238,300,242.12,322,239.09c23.7-3.29,39.36-12.51,52.49-22.36l-41-57.73h2.25a32,32,0,0,0,24.41-52.71L349.49,93.73a10.5,10.5,0,0,1-4.43.28c-35.59-5.4-75.74,2.3-108,8.48-5.57,1.06-10.91,2.09-16,3a130.82,130.82,0,0,1-23,2.09,115.61,115.61,0,0,1-38.46-6.47,10.58,10.58,0,0,1-2.36-1.21l-5.41,6.38A32,32,0,0,0,176.27,159h2.25L139.3,214.2A385.77,385.77,0,0,1,205.44,217.76ZM217.33,84.49c5-.89,10.23-1.9,15.71-2.95,28.75-5.51,63.48-12.12,97.3-10.37l-50-58.88a32,32,0,0,0-48.79,0L171.94,82.62A100,100,0,0,0,217.33,84.49Zm-50.81,272.1c36.73,1.18,57.32,6.7,77.23,12,14.81,4,28.8,7.72,49.09,9.32,47.93,3.78,80.73-8.44,109.27-20.29l-39.53-60.48h7.07a32,32,0,0,0,26.09-50.55h0l-8.88-12.51c-14.8,11-33.74,22.19-61.93,26.1a124.44,124.44,0,0,1-17,1.21c-17.77,0-31.82-4.24-48.59-9.3-15.06-4.54-32.12-9.68-56.93-13.26a369.14,369.14,0,0,0-78.79-2.6l-7.36,10.35a32,32,0,0,0,26.09,50.55h7.06L109.14,358.8A416.07,416.07,0,0,1,166.52,356.59ZM448,489.65H298.67v-48h99.2a32,32,0,0,0,26.74-49.57L414,375.82C387.41,386.94,355.13,400,310.2,400c-6.11,0-12.44-.24-19-.76-22.24-1.77-37.84-5.95-52.93-10-18.74-5-38.12-10.22-72.4-11.32a394.94,394.94,0,0,0-72.05,4.39l-6.37,9.75a32,32,0,0,0,26.73,49.6h99.2v48h-80a10.67,10.67,0,0,0,0,21.33H448a10.67,10.67,0,0,0,0-21.33Z"/></svg>
  Sócio Ambiental</li>

  <li v-on:click="getJuridico()" class="c-menu__li">
  <svg class="c-icone" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 425.2 425.2" style="enable-background:new 0 0 425.2 425.2;" xml:space="preserve"><g id="hammer-2"><path class="st0" d="M2.7,381.6l156.5-156.4c3.7-3.6,9.6-3.6,13.2,0l1.8,1.8l28.4-28.6l-25.9-25.9c-3.6-3.7-3.6-9.6,0-13.2 l80.5-80.5c3.7-3.6,9.6-3.6,13.2,0l75.9,75.9c3.6,3.7,3.6,9.6,0,13.2l-80.5,80.5c-3.7,3.6-9.6,3.6-13.2,0l-25.9-25.9l-28.4,28.4 l1.8,1.8c3.6,3.7,3.6,9.6,0,13.3L43.5,422.5c-3.7,3.6-9.6,3.6-13.2,0L2.9,395C-0.9,391.3-0.9,385.3,2.7,381.6z M152.1,166.4 c-3.7,3.6-9.6,3.6-13.2,0l-38.2-38.2c-3.6-3.7-3.6-9.6,0-13.2l112-112.2c3.7-3.6,9.6-3.6,13.2,0l38.2,38.2c3.6,3.7,3.6,9.6,0,13.2 L152.1,166.4z M310.2,324.5c-3.7,3.6-9.6,3.6-13.2,0l-37.8-37.8c-3.6-3.7-3.6-9.6,0-13.2l112.1-112.3c3.7-3.6,9.6-3.6,13.3,0 l37.8,37.8c3.6,3.7,3.6,9.6,0,13.2L310.2,324.5z"/></g></svg>
  Jurídico</li>
    
  <li v-on:click="getlistrasRestritivas()" class="c-menu__li">
  <svg class="c-icone" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 510.2 510.2" style="enable-background:new 0 0 510.2 510.2;" xml:space="preserve"><path class="st0" d="M255.1,506.1c-67,0-130.1-26.1-177.5-73.5C30.2,385.2,4.1,322.1,4.1,255.1S30.2,125,77.6,77.6C125,30.2,188.1,4.1,255.1,4.1c67,0,130.1,26.1,177.5,73.5C479.9,125,506,188,506,255.1s-26.1,130.1-73.4,177.5C385.2,480,322.1,506.1,255.1,506.1z M99.4,139.7c-24.7,33.3-38.2,73.9-38.2,115.4c0,106.9,87,193.9,193.9,193.9c41.5,0,82-13.5,115.4-38.2L99.4,139.7z M410.8,370.5c24.7-33.3,38.2-73.9,38.2-115.4c0-106.9-87-193.9-193.9-193.9c-41.5,0-82,13.5-115.4,38.2L410.8,370.5z"/><path class="st0" d="M425.5,84.7c-45.5-45.5-106-70.6-170.4-70.6S130.2,39.2,84.7,84.7s-70.6,106-70.6,170.4S39.2,380,84.7,425.5s106,70.6,170.4,70.6S380,471,425.5,425.5s70.5-106,70.5-170.4S471,130.2,425.5,84.7z M459,255.1c0,49.5-17.8,95-47.3,130.4l-287-287c35.4-29.5,80.8-47.3,130.4-47.3C367.5,51.2,459,142.7,459,255.1z M51.2,255.1c0-49.5,17.8-95,47.3-130.4l287,287c-35.4,29.5-80.8,47.3-130.4,47.3C142.7,459,51.2,367.5,51.2,255.1z"/></svg>
  Listras Restritivas</li>

  <li v-on:click="getMidiaInternet()" class="c-menu__li">
  <svg class="c-icone" id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><title>world-globe-earth-glyph</title><path id="_31" data-name="31" d="M256,0C114.9,0,0,114.83,0,256S114.9,512,256,512,512,397.17,512,256,397.16,0,256,0Zm0,494.35C124.61,494.35,17.7,387.42,17.7,256S124.61,17.65,256,17.65,494.3,124.58,494.3,256,387.41,494.35,256,494.35ZM225.16,102.93H236.4V89.57h-9.85V55.14h14V37.58l.81-1.87c2.49-.05,5-.22,7.62-.22A220,220,0,0,1,282,38V49.55h16.11V93.42H285.89l-10.57,10.51-25.61,25.7L236.4,143,225.16,131.7ZM182,45.74l4.16,4.18-7.43,7.36H166.13v12.6h26.66v58.3H172.46V86h-14.1V65.64h-9.07V77.59l-8.79,8.8H119.78l-5.68-5.71A223.12,223.12,0,0,1,182,45.74Zm73.3,326.12H236.4l-9.85,14.07v31.59l-28.81,21.09v37.9L165.41,447V369.77L131,337.43v-39.3L107.15,280.6H86.07L71,265.48V244.74l-10.15-6.27L58,246.16,62.89,249v17.61L50.26,251.1l-6.33-24.61-5.64-1.4V182.15a225.42,225.42,0,0,1,51.13-79.93l70.34.71L157,117.67l-21.09,1.38,2.12,7L143,131.7l-5.62,9.11-16.88-2.07,9.89,13.36L147.15,164l5.62,13.36,7-2.07V140.81h19v4.25h19.68V168.9H190v9.85h-8.46v6.34h11.94l-7.73,7.71-3.13-3.14L175.25,197v6.31L168.6,210l-8.44,8.42-9.84,9.85-6.62,6.65V256h-9.23V244.74H104.33v12.73l29.5,28.09h59v5.62h21.13l23.15,29.47h18.26ZM434.39,241.21V259.5H404.21L389.4,244.74v-9.8h-8.68V248.7l20,20h22.84v16.49l-20.77,20.72v58.3H387V394l-12.29,12.25H345.81V379.71l-15.61-15.54V315.29l-19.39-19.38H270.23l-16-16V239.45L268,225.81h23.15l14.76-14.74h17.62v7.73h54v-9.45H363.88l8-8.11,7.74-7.71h13.28l-8.38-8.34H372l-13.29,13.23V208.8l-14.15-14.23h-8.83l13,13H338.19l-8.43-8.44v-5.63l-12.64-12.6-9.45,9.47-8.1,8.07v14.73H283.4V183.69h6V178.4l3.84-3.85-6.94-7.05-9.2,9.14-7.35-7.4,3.91-3.84V144.34h14.72v8.43l12.58,12.63h9.21v-9.85h28.06v-9.82h11.24v-14h-11.9V118.34h-6.34v26.72l-5,4.89-9.8-4.22-16.86-4.18,1.35-16.14,16.94-12.65,9.78-16.83,18.27-4.22-2.05,8.4,11.9,2.09-.68,8.4,13.32-1.42,6.34-4.2,1.34-7h28.17a223.91,223.91,0,0,1,69.46,162.19c0,3.45-.11,6.84-.27,10.27l-48.88-48.92-4.93,4.93Z" fill="#231f20"/></svg>
  Mídia / Internet</li>

  <li v-on:click="getBensEImoveis()" class="c-menu__li">
  <svg class="c-icone" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 510.2 510.2" style="enable-background:new 0 0 510.2 510.2;" xml:space="preserve"><g><path d="M171.9,155.1C199.6,256,227,356.2,254.4,456.4c0.4-0.1,0.9-0.1,1.3-0.2c27.5-100.2,54.9-200.5,82.5-301.1C282.6,155.1,227.9,155.1,171.9,155.1z"/><path d="M166.2,159.9c-1.2-4.4-3.3-5.1-7.3-5.1c-33.7,0.1-67.4,0.1-101.1,0.1c-13.9,0-27.9,0-43.7,0C91,252.3,166.8,348.4,242.6,444.4c0.9-1.6,0.7-2.5,0.4-3.4C217.4,347.4,191.7,253.7,166.2,159.9z"/><path d="M352.8,154.7c-5.8,0-7.8,1.8-9.3,7.2c-22.4,82.5-45.1,165-67.7,247.5c-3.1,11.5-6.3,23-9.4,34.5c0.4,0.2,0.7,0.4,1.1,0.6c75.8-96.1,151.7-192.3,228.4-289.6c-4,0-6.2,0-8.5,0C442.6,154.9,397.7,155,352.8,154.7z"/><path d="M169.6,147.6c57.2,0,113.8,0,170.9,0c0-1.4,0.1-2.2,0-2.9c-5.8-29-11.7-58-17.4-87c-0.7-3.8-3-3.8-5.9-3.8c-41.4,0-82.8,0.1-124.2,0c-3.7,0-5.4,0.8-6.2,4.8c-5.4,27.9-11.2,55.7-16.8,83.6C169.8,143.9,169.8,145.6,169.6,147.6z"/><path d="M329.7,53.9c0.4,2.8,0.6,4.8,1,6.6c5.5,27.1,11.1,54.2,16.3,81.4c0.9,4.9,2.8,6.1,7.5,6.1c44.7-0.2,89.4-0.1,134.1-0.1c2,0,4,0,6.8,0c-1.1-2.1-1.5-3.1-2.1-4.1c-18.7-28.7-37.4-57.3-56-86.1c-2.1-3.3-4.8-3.8-8.3-3.8c-27.9,0.1-55.7,0-83.6,0C340.4,53.9,335.4,53.9,329.7,53.9z"/><path d="M180.7,54.2c-2.6-0.1-4.3-0.3-6-0.3c-31,0-61.9,0.1-92.9-0.1c-4.7,0-7.4,1.5-9.9,5.4c-18,28-36.2,55.8-54.4,83.7c-0.9,1.3-1.5,2.8-2.6,4.8c49.4,0,97.9,0,146.9,0C168.1,116.7,174.3,85.8,180.7,54.2z"/></g></svg>
  Bens e imóveis</li>

  <li v-on:click="getCadastro()" class="c-menu__li">
  <svg class="c-icone" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 510.2 510.2" style="enable-background:new 0 0 510.2 510.2;" xml:space="preserve"><path d="M298.1,152h-85.7c-24.1,0-40.3,16.3-40.3,40.5c0,47.4,0,94.9,0,142.3c0,22.5,9.4,35.3,31.6,42.4v6.9c0,27.1,0,54.2,0,81.2c0,20.2,10.4,30.6,30.8,30.6h40.3c21.5,0,31.6-10,31.6-31.5c0-27.5,0-54.9,0-82.4c0-2.4-0.9-4.8,3-6.1c19.2-6.3,28.6-19.6,28.6-39.9c0-48,0-96,0-144C338.1,168.5,321.7,152,298.1,152z"/><path d="M255.1,135.4c33.5,0,60.7-27.1,60.7-60.5s-27.1-60.7-60.5-60.7s-60.7,27.1-60.7,60.5c0,0.1,0,0.2,0,0.3C194.5,108.4,221.6,135.4,255.1,135.4C255,135.4,255,135.4,255.1,135.4z"/></svg>
  Cadastro</li>

  <li v-on:click="getFinanceiro()" class="c-menu__li">
  <svg class="c-icone"  version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 510.2 510.2" style="enable-background:new 0 0 510.2 510.2;" xml:space="preserve"><g><path d="M469.7,247.8c-6.9,0.5-10-2-13.4-8.2c-6.8-11.9-14.7-23.2-23.5-33.7c-4.4-5.4-7.2-10.5-7.8-17.5 c-0.6-7.1-3.1-28.7-6.7-60.4l-57,15.6c0,0-3.4,12.9-9.1,13.9c-1.3,0.2-3.1-0.1-5.4-2.1c-22.5-6.5-75-18.3-134.3,2.2 c-18.9,6.5-77.8,27.2-104.2,81.9c-4.6,9.5-8,19.5-9.9,29.9c-14.4,0.7-31.4,0.7-44-1.5c-3.6-0.5-7-1.8-10-3.8 c-3.5-2.5-8.1-7.5-10.1-17.5c-1.2-6-2.1-17.4,5.7-26.4c10-11.5,25.7-9.4,26.3-9.3c5.2,1,10.2-2.4,11.2-7.7S75,193,69.8,192 c-0.3,0-0.5-0.1-0.8-0.1c-2.7-0.4-27.1-3.4-43.6,15.7c-9.7,11.3-13.3,26.4-10,42.7s11.6,25,17.9,29.4c5.3,3.6,11.3,6,17.7,7 c9.3,1.7,20.3,2.2,31.3,2.2c4.9,0,9.7-0.1,14.4-0.3c0.3,23.2,8.8,45.5,24.6,66.8c7.1,9.5,16.3,17.4,24.8,25.7 c2.7,2.6,4,4.5,3.3,8.7c-3.3,18-6,36.2-9.1,55.1c13.7,2.3,27,4.4,40.3,6.7c6.9,1.2,13.8,2.7,20.7,4.1h4.2c2.1-13,4.3-26.1,6.5-39.7 c48.2,14.1,95.5,13.8,143.1-0.6l6.6,40.3h4.2c15.3-2.7,30.7-5.5,46-8.2c4.7-0.9,9.5-1.7,15.1-2.6c-2.1-13.2-3.4-26.2-6.5-38.8 c-3.7-14.8-3.4-26.2,10.6-36.7c13.4-10.1,21.9-25.3,28.3-41c1.5-3.6,3.2-4.9,7-4.8c9.8,0.2,19.7,0.1,29.9,0.1v-76 C487.4,247.7,478.5,247.2,469.7,247.8z M364.6,279.4c-11.8,0-21.3-9.6-21.3-21.3c0-11.8,9.6-21.3,21.3-21.3 c11.8,0,21.3,9.5,21.3,21.3C385.9,269.8,376.4,279.3,364.6,279.4C364.6,279.4,364.6,279.4,364.6,279.4z"/><path d="M203.1,130.4c25.4-8.7,52-13.1,78.8-13c16.4,0,32.9,1.6,49,4.7l2.4-0.6c-2.3-27-18.8-50.8-44.7-61.1c-6.4-2.6-13.3-3.9-19.9-5.9h-16.8c-7.7,2.4-15.9,3.9-23.1,7.3c-28.7,13.5-45.7,44.6-41.6,74.6C192.4,134.3,197.6,132.2,203.1,130.4z"/></g></svg>
  Financeiro</li>

</ul>

</div>

<div class="c-container">
 <p class="c-container__nome">Ordernar</p>
 <select class="c-container__select">
  <option>Lançamento</option>
  <option>Valores</option>
 </select>
</div>
<div class="c-containerCard">
  <div class="c-card">
    <div class="c-card--icone--titulo">
  <svg class="c-icone" id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 512"><defs><linearGradient id="linear-gradient" x1="256" y1="491.29" x2="256" y2="20.71" gradientUnits="userSpaceOnUse"><stop offset="0" stop-color="#231f20"/><stop offset="1" stop-color="#58595b"/></linearGradient></defs><title>briefcase</title><path d="M512,229.15V465.68a25.68,25.68,0,0,1-25.61,25.61H25.59A25.66,25.66,0,0,1,0,465.68V229.15H230.5V293.7h51V229.15ZM0,205.2V149.39a25.68,25.68,0,0,1,25.59-25.61H152.91V58a37.37,37.37,0,0,1,37.32-37.31H321.75A37.37,37.37,0,0,1,359.07,58v65.76H486.39A25.7,25.7,0,0,1,512,149.39V205.2H281.48V185.46h-51V205.2Zm186.71-81.42H325.28V58a3.54,3.54,0,0,0-3.53-3.53H190.23A3.54,3.54,0,0,0,186.71,58Z" fill-rule="evenodd" fill="url(#linear-gradient)"/></svg>
    <h1 class="c-card__titulo">Profissional</h1>
    </div>
    <div class="c-card__itens">
      <span class="c-card__itens--valor">RS 29,99</span>
      <a class="c-card__itens--link">Saiba Mais</a>
    </div>
  </div>

  <div class="c-card">
    <div class="c-card--icone--titulo">
  <svg class="c-icone"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><defs><!-- <style>.cls-1{fill:#141f38;}</style> --></defs><title>bank-glyph</title><path class="cls-1" d="M166.41,243.21v128a12.8,12.8,0,0,1,12.8,12.8v25.6h-128V384A12.8,12.8,0,0,1,64,371.2v-128a12.8,12.8,0,0,1-12.8-12.8v-25.6h128v25.6A12.8,12.8,0,0,1,166.41,243.21Zm294.38-12.8v-25.6h-128v25.6a12.8,12.8,0,0,0,12.8,12.8v128a12.8,12.8,0,0,0-12.8,12.8v25.6h128V384A12.8,12.8,0,0,0,448,371.2v-128A12.8,12.8,0,0,0,460.78,230.41ZM1.1,154.76c-3.83-15,2.55-29.93,15.87-37.22L210.32,11.74a94.76,94.76,0,0,1,91.36,0L495,117.53c13.32,7.29,19.7,22.25,15.87,37.22-3.74,14.62-16.18,24.45-31,24.45H32.06C17.28,179.21,4.84,169.38,1.1,154.76ZM217.6,89.61A38.4,38.4,0,1,0,256,51.21,38.4,38.4,0,0,0,217.6,89.61ZM448,435.2H64a64.07,64.07,0,0,0-64,64V512H512V499.2A64.07,64.07,0,0,0,448,435.2ZM320,230.41v-25.6H192v25.6a12.8,12.8,0,0,0,12.8,12.8v128A12.8,12.8,0,0,0,192,384v25.6H320V384a12.8,12.8,0,0,0-12.8-12.8v-128A12.8,12.8,0,0,0,320,230.41Z"/></svg>
    <h1 class="c-card__titulo">Refuladores</h1>
    <p class="c-card__texto">
      O aplicativo Balanço Patrimonial realiza a consulta de todos os balanços
      que são publicados nos Diários Oficiais de empresas S.A., de caítal aberto
      e limitadas (LTDA) de grande porte.
    </p>
    </div>
    <div class="c-card__itens">
      <span class="c-card__itens--valor">RS 29,99</span>
      <a class="c-card__itens--link">Saiba Mais</a>
    </div>
  </div>
</div>
</div>
</template>

<script>

import { api } from "@/services.js";
export default {
  name: 'Home',
  components: {
 
  },
  data() {
    return {
      
  }

},
 methods: {


  getAllList(){
    api
          .get('/tudo')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      },
      getProfissionais(){
          api
          .get('/profissionais')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      },
     getReguladores(){
          api
          .get('/reguladores')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      },
      getSocioAmbiental(){
         api
          .get('/socio-ambiental')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      },
      getJuridico(){
         api
          .get('/juridico')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      },
      getlistrasRestritivas(){
         api
          .get('/listras-restritivas')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      },
      getMidiaInternet(){
          api
          .get('/midia-internet')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      },
      getBensEImoveis(){
         api
          .get('/bens-e-imoveis')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      },
      getCadastro(){
          api
          .get('/cadastro')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      },
      getFinanceiro(){
         api
          .get('/financeiro')
          .then((response) => {
            console.log(response)
          })
          .catch((error) => console.log(error))
          .finally(() => {
          
          })
      }

  }


    
  }

</script>
<style scoped>

.c-menu__ul{
display: flex;
justify-content: center;
flex-wrap: wrap;
}
.c-menu__li{
 
  display: flex;
  flex-direction: column;
  justify-content:center;
  align-items: center;
  cursor: pointer;
/*   background: #eef1f3; */
    background: #fafafa;
  
  color: #80888e;
  font-size: 13px;
  border: 1px solid #a7a7a71a;
  padding: 10px 0px;
/*   min-width: 160px;
  max-width: 160px; */
  min-width: 115px;
  max-width: 115px;
}
.c-menu__li:hover{
    border-radius: 5px;
    border: 3px solid #e96a0a;
    background: #ff6e00;
    color: #ffffff91;
}
.c-menu__li:hover > svg path{
  fill: white;
}
.c-menu__li > svg path{
  fill: #696969;
}
.c-icone{
  max-width: 20px;
  margin-bottom: 10px;
}
.c-menu__span{
  font-size: 12px;  
  padding-top: 10px;
  color: #80888e;
}
.c-container{
  padding: 20px 0px;
  display: flex;
  align-items: center;
}
.c-container__nome{
font-size: 12px;
text-transform: uppercase;
font-weight: bold;
margin-right: 10px;
}
.c-container__select{
  cursor: pointer;
  font-weight: bold;
  color: #696969;
  width:200px;
  padding: 5px;
  border-color: #9e9e9e;
}
.c-containerCard{
display: flex;
flex-direction: row;
}
.c-card{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin: 10px 10px;
    max-width: 300px;
    min-width: 300px;
        min-height: 270px;
    max-height: 270px;
  /*   min-height: 300px;
    max-height: 300px; */
    border-radius: 4px;
    box-shadow: 0px 0px 5px 0px #00000012;
    margin: 10px 10px;
 
}
.c-card--icone--titulo{
padding-top: 30px;
 /*  padding: 30px 30px; */
}
.c-card__titulo{
    font-size: 1.3rem;
  color: #828282;
}
.c-card__texto{
  padding-top: 10px;
  color: #bcbcbc;
  font-size: 14px;
  /*   line-height: 14px; */
    margin: 10px;
}
 svg path{
  fill: #ff6e00;
}

 .c-card__itens{
    display: flex;
    color: white;
    padding: 10px;
    background-image: linear-gradient(to right, rgb(255 99 1 / 57%), rgb(255 104 0));
    align-items: center;
    flex-direction: row;
    justify-content: space-between;
    border-radius: 0px 0px 4px 4px;
 }
 .c-card__itens--valor{
margin-left: 10px;
 }
.c-card__itens--link{
  cursor: pointer;
margin-right: 5px;
}
  
</style>