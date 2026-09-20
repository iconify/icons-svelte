<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj8h-z_we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dj8h-z_we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ungroup-objects" {...props}></Icon>
