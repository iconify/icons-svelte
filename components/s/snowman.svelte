<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us_k6cbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="us_k6cbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:snowman" {...props}></Icon>
