<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk8pohd4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yk8pohd4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-wrap-bold" {...props}></Icon>
