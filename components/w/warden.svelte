<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zu6ek4h1t.css';
import '../../css/r/rgbhf6bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":77};
const content = `<g class="cuyn6tgcc"><path class="zu6ek4h1t"/><path class="rgbhf6bcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:warden" {...props}></Icon>
