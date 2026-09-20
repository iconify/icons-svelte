<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djh599ahd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djh599ahd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:video-solid" {...props}></Icon>
