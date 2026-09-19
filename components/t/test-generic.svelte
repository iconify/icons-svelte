<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7rongbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7rongbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:test-generic" {...props}></Icon>
