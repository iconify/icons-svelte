<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks1b49xoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks1b49xoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spotify-line" {...props}></Icon>
