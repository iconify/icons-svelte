<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke-b1vt8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ke-b1vt8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shapes" {...props}></Icon>
