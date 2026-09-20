<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_5qt8t0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_5qt8t0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wireless-charging-fill" {...props}></Icon>
