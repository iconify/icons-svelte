<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b829x45jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b829x45jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wind-energy" {...props}></Icon>
