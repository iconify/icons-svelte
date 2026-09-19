<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbi7ckrjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dbi7ckrjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:stream" {...props}></Icon>
