<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5n4f734v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m5n4f734v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:start-data-analysis" {...props}></Icon>
