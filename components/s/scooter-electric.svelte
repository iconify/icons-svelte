<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl5p9ubwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl5p9ubwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scooter-electric" {...props}></Icon>
