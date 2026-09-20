<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8wgp4bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t8wgp4bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:send-right-filled" {...props}></Icon>
