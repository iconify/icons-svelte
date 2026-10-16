<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcjmwhbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dcjmwhbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wood-pellets-48" {...props}></Icon>
