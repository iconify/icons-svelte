<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxix2hbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qxix2hbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:truck-monster-solid" {...props}></Icon>
