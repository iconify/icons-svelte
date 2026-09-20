<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/pel4bdbze.css';
import '../../css/s/s-xpk0xxq.css';
import '../../css/a/axh_y-hbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pel4bdbze"/><path class="s-xpk0xxq"/><path class="axh_y-hbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:test-tube-diagonal-sharp-duotone" {...props}></Icon>
