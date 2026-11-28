<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn4j-ibjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn4j-ibjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:router" {...props}></Icon>
