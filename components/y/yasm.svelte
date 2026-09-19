<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-_hd-q4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":462,"height":512};
const content = `<path class="m-_hd-q4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:yasm" {...props}></Icon>
