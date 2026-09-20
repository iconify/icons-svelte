<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-92lpsuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n-92lpsuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-plus-solid" {...props}></Icon>
