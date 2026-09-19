<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh97r9dck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="uh97r9dck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:skip-previous" {...props}></Icon>
