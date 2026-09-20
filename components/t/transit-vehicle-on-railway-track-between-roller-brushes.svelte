<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcnahacaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gcnahacaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:transit-vehicle-on-railway-track-between-roller-brushes" {...props}></Icon>
