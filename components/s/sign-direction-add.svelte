<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne-y8d_hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne-y8d_hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sign-direction-add" {...props}></Icon>
