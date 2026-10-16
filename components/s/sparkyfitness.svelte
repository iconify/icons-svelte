<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyogtrxua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":517.4,"height":517.4,"left":74.1,"top":22.2};
const content = `<path class="cyogtrxua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sparkyfitness" {...props}></Icon>
