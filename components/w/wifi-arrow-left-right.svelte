<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etss8k7ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etss8k7ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-arrow-left-right" {...props}></Icon>
