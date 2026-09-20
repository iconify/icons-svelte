<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrciqznso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrciqznso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:upload-box" {...props}></Icon>
