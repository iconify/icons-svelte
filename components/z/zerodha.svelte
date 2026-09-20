<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upn1fdbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upn1fdbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zerodha" {...props}></Icon>
