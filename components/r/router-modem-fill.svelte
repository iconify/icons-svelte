<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3t8upb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3t8upb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:router-modem-fill" {...props}></Icon>
