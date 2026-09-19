<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl3uy_3rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kl3uy_3rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:shotgrid-wordmark" {...props}></Icon>
