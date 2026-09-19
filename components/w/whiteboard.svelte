<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2srrkj6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="m2srrkj6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:whiteboard" {...props}></Icon>
