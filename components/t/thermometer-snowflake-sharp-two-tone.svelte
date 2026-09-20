<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/dj05c4b-z.css';
import '../../css/y/y28btccsp.css';
import '../../css/x/xcyk673ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dj05c4b-z"/><path class="y28btccsp"/><path class="xcyk673ka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:thermometer-snowflake-sharp-two-tone" {...props}></Icon>
