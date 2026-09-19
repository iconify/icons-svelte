<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmok94b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vmok94b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sls" {...props}></Icon>
