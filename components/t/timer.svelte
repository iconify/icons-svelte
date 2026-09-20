<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwww74b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vwww74b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:timer" {...props}></Icon>
