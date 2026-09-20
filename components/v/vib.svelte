<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4ypf7qrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4ypf7qrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vib" {...props}></Icon>
