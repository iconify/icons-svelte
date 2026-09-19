<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dthzkk69i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dthzkk69i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:stop" {...props}></Icon>
