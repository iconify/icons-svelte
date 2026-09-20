<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isp18v05x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isp18v05x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trolley-arrow-down" {...props}></Icon>
