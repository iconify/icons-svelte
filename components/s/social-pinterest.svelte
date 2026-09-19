<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl3i8zbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="rl3i8zbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-pinterest" {...props}></Icon>
