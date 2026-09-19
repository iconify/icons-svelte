<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8_grzszs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f8_grzszs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:source" {...props}></Icon>
