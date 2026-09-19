<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmifki02x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1600};
const content = `<path class="xmifki02x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:star-half-o" {...props}></Icon>
