<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-7em1b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-7em1b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:water-heater-error" {...props}></Icon>
