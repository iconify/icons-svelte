<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a49x2calt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a49x2calt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seat-flat" {...props}></Icon>
