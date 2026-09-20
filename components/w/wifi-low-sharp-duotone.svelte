<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/c3iputbuh.css';
import '../../css/v/vr3n6i7pr.css';
import '../../css/c/chh9m8bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c3iputbuh"/><path class="vr3n6i7pr"/><path class="chh9m8bfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wifi-low-sharp-duotone" {...props}></Icon>
