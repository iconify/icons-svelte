<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6i-o7wkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s6i-o7wkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tipi-campsites" {...props}></Icon>
