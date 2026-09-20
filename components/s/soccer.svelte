<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz9vejtvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uz9vejtvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:soccer" {...props}></Icon>
