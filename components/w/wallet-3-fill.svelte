<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9607gb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9607gb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wallet-3-fill" {...props}></Icon>
