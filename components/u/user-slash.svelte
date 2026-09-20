<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgnp9cbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cgnp9cbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-slash" {...props}></Icon>
