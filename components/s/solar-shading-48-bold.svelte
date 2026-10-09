<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7lr-0b7o.css';
import '../../css/d/decjvjero.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t7lr-0b7o"/><path class="decjvjero"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-shading-48-bold" {...props}></Icon>
