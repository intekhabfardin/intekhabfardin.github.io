link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet"
.table
  .table-cell
    .container
      | <svg class="background-svg" width="400px" height="300px" viewBox="0 0 400 300" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><defs><filter x="-50%" y="-50%" width="200%" height="200%" filterUnits="objectBoundingBox" id="filter-1"><feOffset dx="0" dy="10" in="SourceAlpha" result="shadowOffsetOuter1"></feOffset><feGaussianBlur stdDeviation="2" in="shadowOffsetOuter1" result="shadowBlurOuter1"></feGaussianBlur><feColorMatrix values="0 0 0 0 0   0 0 0 0 0   0 0 0 0 0  0 0 0 0.095 0" in="shadowBlurOuter1" type="matrix" result="shadowMatrixOuter1"></feColorMatrix><feOffset dx="0" dy="1" in="SourceAlpha" result="shadowOffsetInner1"></feOffset><feGaussianBlur stdDeviation="1.5" in="shadowOffsetInner1" result="shadowBlurInner1"></feGaussianBlur><feComposite in="shadowBlurInner1" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="shadowInnerInner1"></feComposite><feColorMatrix values="0 0 0 0 0.647959184   0 0 0 0 0.549016553   0 0 0 0 0.549016553  0 0 0 0.35 0" in="shadowInnerInner1" type="matrix" result="shadowMatrixInner1"></feColorMatrix><feMerge><feMergeNode in="shadowMatrixOuter1"></feMergeNode><feMergeNode in="SourceGraphic"></feMergeNode><feMergeNode in="shadowMatrixInner1"></feMergeNode></feMerge></filter></defs><g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g id="Artboard-1" fill="#8B65E4"><path d="M187.785156,200 L180,232 L66,232 L58.2148437,200 L187.785156,200 Z" id="Rectangle-1" filter="url(#filter-1)"></path><path d="M349.760339,49.1234675 L375.905579,277.733833 L199.999999,277.733834 L43.9648432,143.710938 L349.760339,49.1234675 Z" id="Triangle-1" filter="url(#filter-1)"></path><path d="M399.8936,96.1889997 L29.4623426,250.140552 L0,36.4302476 L399.8936,96.1889997 Z" id="Triangle-2" filter="url(#filter-1)"></path></g></g></svg>
      .container-info
        h1
          ' Hey!
          br
          ' I'm
          span Intekhab Fardin
          ',
          span.info a marketing student
        .box
          a.box-item href="https://www.linkedin.com/in/annabatura" target="_blank"
            i.fa.fa-linkedin
          a.box-item href="https://codepen.io/Anna_Batura/" target="_blank"
            i.fa.fa-codepen
          a.box-item href="https://twitter.com/BrawadaCom" target="_blank"
            i.fa.fa-twitter

