<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r-do9_buf.css';
import '../../css/b/b-w7m1bnc.css';
import '../../css/p/p-t_3wb-z.css';
import '../../css/f/f00_0pbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r-do9_buf"/><path class="b-w7m1bnc"/><path class="p-t_3wb-z"/><path class="f00_0pbwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:washing-machine-minimalistic-linear" {...props}></Icon>
