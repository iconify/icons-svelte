<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_1oyq81x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_1oyq81x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shoe-sneaker" {...props}></Icon>
