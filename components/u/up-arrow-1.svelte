<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m79bmj2zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m79bmj2zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:up-arrow-1" {...props}></Icon>
