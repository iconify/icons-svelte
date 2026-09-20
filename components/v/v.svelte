<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpxc1-b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fpxc1-b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:v" {...props}></Icon>
