<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww-0lbb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":41,"height":41};
const content = `<path class="ww-0lbb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:uv" {...props}></Icon>
