<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyj7ucbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cyj7ucbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:tunnel" {...props}></Icon>
