<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8u2cz3tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t8u2cz3tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:xmos" {...props}></Icon>
