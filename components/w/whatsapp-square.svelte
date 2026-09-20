<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohn5t9b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ohn5t9b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:whatsapp-square" {...props}></Icon>
