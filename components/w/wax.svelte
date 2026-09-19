<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwo1-zbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lwo1-zbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:wax" {...props}></Icon>
