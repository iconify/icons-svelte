<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5ygh_b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="t5ygh_b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-low" {...props}></Icon>
