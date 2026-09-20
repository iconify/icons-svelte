<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyoctf0bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eyoctf0bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-graduate-solid" {...props}></Icon>
