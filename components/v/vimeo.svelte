<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy_j5wugz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xy_j5wugz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:vimeo" {...props}></Icon>
