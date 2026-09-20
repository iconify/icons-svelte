<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/md1uaibwm.css';
import '../../css/f/fblsodb-h.css';
import '../../css/k/kxcghxbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="md1uaibwm"/><path class="fblsodb-h"/><path class="kxcghxbfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-vertical-bold" {...props}></Icon>
