<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnhydoens.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnhydoens"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-box-multiple" {...props}></Icon>
