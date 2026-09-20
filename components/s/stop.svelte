<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6cablbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f6cablbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:stop" {...props}></Icon>
