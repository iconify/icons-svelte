<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnuus6brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnuus6brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-frame-2-broken" {...props}></Icon>
