<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssck75ytp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ssck75ytp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:telegram-plane" {...props}></Icon>
