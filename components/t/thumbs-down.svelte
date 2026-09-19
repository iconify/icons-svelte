<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm0ynk4zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zm0ynk4zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:thumbs-down" {...props}></Icon>
