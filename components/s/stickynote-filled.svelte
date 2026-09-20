<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zdy1asb3s.css';
import '../../css/u/ulof31eud.css';
import '../../css/m/mdxy78itc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zdy1asb3s"/><path class="ulof31eud"/><path class="mdxy78itc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stickynote-filled" {...props}></Icon>
