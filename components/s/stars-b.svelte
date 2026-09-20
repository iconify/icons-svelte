<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it92y3bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it92y3bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:stars-b" {...props}></Icon>
