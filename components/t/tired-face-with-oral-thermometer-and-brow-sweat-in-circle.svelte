<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ndmlpoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p7ndmlpoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-with-oral-thermometer-and-brow-sweat-in-circle" {...props}></Icon>
