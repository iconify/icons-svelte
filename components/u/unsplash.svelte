<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw2z57h3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rw2z57h3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:unsplash" {...props}></Icon>
