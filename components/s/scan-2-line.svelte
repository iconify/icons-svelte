<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tged_ebbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tged_ebbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scan-2-line" {...props}></Icon>
