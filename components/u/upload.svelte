<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpx8s0bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lpx8s0bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:upload" {...props}></Icon>
