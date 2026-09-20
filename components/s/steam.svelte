<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-e4w-eol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m-e4w-eol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:steam" {...props}></Icon>
