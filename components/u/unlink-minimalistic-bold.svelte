<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nvf9vrbds.css';
import '../../css/f/fa1zc_bfw.css';
import '../../css/f/fe0h04b0a.css';
import '../../css/l/lj54e5b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nvf9vrbds"/><path class="fa1zc_bfw"/><path class="fe0h04b0a"/><path class="lj54e5b6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:unlink-minimalistic-bold" {...props}></Icon>
