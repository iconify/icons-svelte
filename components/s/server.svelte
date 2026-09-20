<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj9bm4bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cj9bm4bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:server" {...props}></Icon>
