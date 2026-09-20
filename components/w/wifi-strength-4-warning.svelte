<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npwzcdxdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npwzcdxdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-4-warning" {...props}></Icon>
