<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ep_7h_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5ep_7h_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-minus-outline" {...props}></Icon>
