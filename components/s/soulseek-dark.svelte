<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f40n46bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f40n46bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:soulseek-dark" {...props}></Icon>
