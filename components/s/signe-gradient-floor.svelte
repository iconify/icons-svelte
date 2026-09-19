<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2z-v1b9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2z-v1b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:signe-gradient-floor" {...props}></Icon>
