<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3nly0bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3nly0bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:stadium" {...props}></Icon>
