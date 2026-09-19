<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8oxywb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i8oxywb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:zec" {...props}></Icon>
