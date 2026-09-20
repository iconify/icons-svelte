<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evs7p7bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evs7p7bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-half-full" {...props}></Icon>
