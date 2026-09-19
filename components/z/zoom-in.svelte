<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqv5abcjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":376,"height":384};
const content = `<path class="wqv5abcjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:zoom-in" {...props}></Icon>
