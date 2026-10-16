<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs87d4bxt.css';
import '../../css/w/wexnw_bks.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rs87d4bxt"/><path class="wexnw_bks"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:suction-bucket-20" {...props}></Icon>
