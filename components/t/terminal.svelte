<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u46mg0b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u46mg0b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:terminal" {...props}></Icon>
