<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzf7p8kpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tzf7p8kpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:web3js" {...props}></Icon>
