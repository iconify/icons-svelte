<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q90m5qb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q90m5qb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-shutoff" {...props}></Icon>
