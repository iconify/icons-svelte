<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_z4w9s3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s_z4w9s3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wifi-low-solid" {...props}></Icon>
