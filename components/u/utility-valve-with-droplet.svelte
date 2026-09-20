<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6vm9d3lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c6vm9d3lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-valve-with-droplet" {...props}></Icon>
