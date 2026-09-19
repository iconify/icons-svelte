<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c400xacav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="c400xacav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-ninja" {...props}></Icon>
