<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m45m7yblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m45m7yblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:scan-qr-code" {...props}></Icon>
