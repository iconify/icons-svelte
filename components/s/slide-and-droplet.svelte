<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjldgvq9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gjldgvq9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:slide-and-droplet" {...props}></Icon>
