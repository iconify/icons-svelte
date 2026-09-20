<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/b/bi9ermbmx.css';
import '../../css/s/sudo-1bgw.css';
import '../../css/o/osxy73eeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bi9ermbmx"/><path class="sudo-1bgw"/><path class="osxy73eeo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wifi-x-sharp-two-tone" {...props}></Icon>
