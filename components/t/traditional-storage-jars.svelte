<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1vnq8g0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i1vnq8g0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:traditional-storage-jars" {...props}></Icon>
