<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/e/eazxt60nh.css';
import '../../css/f/frhqtptbh.css';
import '../../css/m/mo03jbcfd.css';
import '../../css/h/h5k7meb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="eazxt60nh wm-deco"/><path class="frhqtptbh wm-deco"/><path class="mo03jbcfd"/><path class="h5k7meb4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trending-up-blueprint" {...props}></Icon>
