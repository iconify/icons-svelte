<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0zc6hbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m0zc6hbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:triangle-outline" {...props}></Icon>
