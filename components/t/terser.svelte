<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_hcr-bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_hcr-bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:terser" {...props}></Icon>
