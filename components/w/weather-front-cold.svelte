<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5eoifbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i5eoifbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:weather-front-cold" {...props}></Icon>
