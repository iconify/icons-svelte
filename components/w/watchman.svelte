<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgf-f2bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lgf-f2bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:watchman" {...props}></Icon>
