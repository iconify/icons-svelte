<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z03t39b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z03t39b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:satellite-weather" {...props}></Icon>
