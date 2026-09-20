<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lgn46h21v.css';
import '../../css/o/oai5is-6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<rect class="cuyn6tgcc"/><g class="cuyn6tgcc"><path class="lgn46h21v"/><g transform="translate(-18.436 -431.962)"><circle/><path class="oai5is-6o"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:uwsgi" {...props}></Icon>
