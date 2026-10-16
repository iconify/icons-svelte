<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-1w69bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-1w69bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:three-phase-20" {...props}></Icon>
