<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0py9l3oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r0py9l3oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:umbrella-beach" {...props}></Icon>
