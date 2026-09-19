<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/equl4-74y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="equl4-74y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:whatsapp-square" {...props}></Icon>
