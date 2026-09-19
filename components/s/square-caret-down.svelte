<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3j1eqb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="d3j1eqb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:square-caret-down" {...props}></Icon>
