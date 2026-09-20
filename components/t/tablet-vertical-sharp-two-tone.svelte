<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/q/qd_1w_bij.css';
import '../../css/p/p735-fm4x.css';
import '../../css/z/z9i4rfbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qd_1w_bij"/><path class="p735-fm4x"/><path class="z9i4rfbjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tablet-vertical-sharp-two-tone" {...props}></Icon>
