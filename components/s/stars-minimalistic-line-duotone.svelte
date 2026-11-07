<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/e/e_5b2ub9c.css';
import '../../css/v/vkmh5nbgy.css';
import '../../css/t/ten00y47l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="e_5b2ub9c"/><path class="vkmh5nbgy"/><path class="ten00y47l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-minimalistic-line-duotone" {...props}></Icon>
