<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2srieiak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m2srieiak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-with-oral-thermometer-and-brow-sweat-in-circle-outline" {...props}></Icon>
