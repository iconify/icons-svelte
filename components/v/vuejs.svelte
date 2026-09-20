<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw_djzbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bw_djzbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vuejs" {...props}></Icon>
