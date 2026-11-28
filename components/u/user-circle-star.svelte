<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn0tq4l1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pn0tq4l1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:user-circle-star" {...props}></Icon>
