<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgkl83cth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":447,"height":512};
const content = `<path class="wgkl83cth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:scrutinizer" {...props}></Icon>
