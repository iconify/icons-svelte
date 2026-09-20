<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m4trolbvo.css';
import '../../css/h/hcbcxsj0q.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/f/fbhog9-zq.css';
import '../../css/c/cjfc5abjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m4trolbvo"/><path clip-rule="evenodd" class="hcbcxsj0q"/><g class="mc2zb0bvp"><path class="fbhog9-zq"/><path class="cjfc5abjr"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallpaper-bold-duotone" {...props}></Icon>
