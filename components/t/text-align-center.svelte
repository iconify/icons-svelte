<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye3ug6bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ye3ug6bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-align-center" {...props}></Icon>
