<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuq4lib0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uuq4lib0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-color" {...props}></Icon>
