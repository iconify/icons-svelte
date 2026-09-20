<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu592ej9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yu592ej9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:webcam-cancelled" {...props}></Icon>
