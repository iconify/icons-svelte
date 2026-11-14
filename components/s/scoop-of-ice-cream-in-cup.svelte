<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf446b7gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wf446b7gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:scoop-of-ice-cream-in-cup" {...props}></Icon>
