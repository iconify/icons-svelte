<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk8lclvhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xk8lclvhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:view-grid" {...props}></Icon>
