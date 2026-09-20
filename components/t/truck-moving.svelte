<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owo0b-9yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="owo0b-9yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:truck-moving" {...props}></Icon>
