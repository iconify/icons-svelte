<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u88g-d3nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u88g-d3nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:traccar" {...props}></Icon>
