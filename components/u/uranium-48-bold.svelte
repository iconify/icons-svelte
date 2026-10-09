<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9jey4b7b.css';
import '../../css/y/y5r8golxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l9jey4b7b"/><path class="y5r8golxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:uranium-48-bold" {...props}></Icon>
