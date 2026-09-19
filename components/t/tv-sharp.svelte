<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1u8gz3hx.css';
import '../../css/g/gdktam-6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1u8gz3hx"/><rect class="gdktam-6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tv-sharp" {...props}></Icon>
