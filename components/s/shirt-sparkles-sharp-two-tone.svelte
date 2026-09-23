<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vhj6biypl.css';
import '../../css/l/l9gqw4bde.css';
import '../../css/t/t-fa8-bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vhj6biypl"/><path class="l9gqw4bde"/><path class="t-fa8-bok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shirt-sparkles-sharp-two-tone" {...props}></Icon>
