<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua5l0n7zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ua5l0n7zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:topic" {...props}></Icon>
