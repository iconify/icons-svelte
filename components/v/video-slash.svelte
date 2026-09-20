<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2qbkyvda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k2qbkyvda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:video-slash" {...props}></Icon>
