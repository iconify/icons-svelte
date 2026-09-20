<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rknwa3bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rknwa3bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:volleyball-15" {...props}></Icon>
