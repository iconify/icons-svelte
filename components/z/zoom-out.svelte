<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmpx80b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":376,"height":384};
const content = `<path class="tmpx80b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:zoom-out" {...props}></Icon>
