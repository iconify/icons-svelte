<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y363cibox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="y363cibox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:u-square" {...props}></Icon>
