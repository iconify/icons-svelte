<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf_oem-1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf_oem-1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-stop" {...props}></Icon>
