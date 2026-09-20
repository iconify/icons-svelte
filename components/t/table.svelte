<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyw4_cb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wyw4_cb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:table" {...props}></Icon>
