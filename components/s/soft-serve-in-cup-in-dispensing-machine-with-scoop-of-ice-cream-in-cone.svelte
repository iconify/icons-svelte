<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcw2bfu7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xcw2bfu7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:soft-serve-in-cup-in-dispensing-machine-with-scoop-of-ice-cream-in-cone" {...props}></Icon>
