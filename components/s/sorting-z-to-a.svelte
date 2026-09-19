<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wavd5lb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wavd5lb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sorting-z-to-a" {...props}></Icon>
