<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uh6tm789e.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/l/lvn50tezb.css';
import '../../css/y/yfbk6go2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uh6tm789e"/><g class="mc2zb0bvp"><path class="lvn50tezb"/><path class="yfbk6go2x"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-2-bold-duotone" {...props}></Icon>
