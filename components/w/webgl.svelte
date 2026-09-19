<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7d-mk6up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s7d-mk6up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:webgl" {...props}></Icon>
