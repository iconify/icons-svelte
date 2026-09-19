<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maq3uib2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="maq3uib2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:windows8-wordmark" {...props}></Icon>
