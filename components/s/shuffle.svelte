<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3mw5zbrj.css';
import '../../css/l/lf7w2ibjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d3mw5zbrj"/><path class="lf7w2ibjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:shuffle" {...props}></Icon>
