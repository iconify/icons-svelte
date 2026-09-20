<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usl5inb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="usl5inb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voron-dark" {...props}></Icon>
