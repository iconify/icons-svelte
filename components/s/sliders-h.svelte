<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olt9o2bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="olt9o2bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sliders-h" {...props}></Icon>
