<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4txutbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4txutbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:teapot" {...props}></Icon>
