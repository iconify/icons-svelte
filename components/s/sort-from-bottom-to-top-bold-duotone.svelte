<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/ralvgguwp.css';
import '../../css/r/rzbequbko.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/i/ik91aybia.css';
import '../../css/n/ntcy9jf7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ralvgguwp"/><path class="rzbequbko"/><g class="mc2zb0bvp"><path class="ik91aybia"/><path class="ntcy9jf7q"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-from-bottom-to-top-bold-duotone" {...props}></Icon>
