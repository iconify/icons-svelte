<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0_97tc8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="a0_97tc8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:skull" {...props}></Icon>
