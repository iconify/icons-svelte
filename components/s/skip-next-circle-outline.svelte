<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/calg-m4sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="calg-m4sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip-next-circle-outline" {...props}></Icon>
