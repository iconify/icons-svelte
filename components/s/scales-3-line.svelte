<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld_nlfa0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld_nlfa0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scales-3-line" {...props}></Icon>
