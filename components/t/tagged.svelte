<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqgla7d8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="rqgla7d8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tagged" {...props}></Icon>
