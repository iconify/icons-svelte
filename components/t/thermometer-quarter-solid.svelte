<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_e6p9bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w_e6p9bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:thermometer-quarter-solid" {...props}></Icon>
