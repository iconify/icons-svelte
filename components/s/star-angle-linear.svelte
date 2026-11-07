<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf_73mb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf_73mb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-angle-linear" {...props}></Icon>
