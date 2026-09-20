<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co5gvya4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="co5gvya4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:thumbs-up" {...props}></Icon>
