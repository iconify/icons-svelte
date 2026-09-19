<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a97m5wlzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a97m5wlzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:worship-christian" {...props}></Icon>
