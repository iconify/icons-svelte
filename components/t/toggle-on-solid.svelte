<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrxxgab7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rrxxgab7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:toggle-on-solid" {...props}></Icon>
