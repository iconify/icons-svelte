<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuvhlpdhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uuvhlpdhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:star2off" {...props}></Icon>
