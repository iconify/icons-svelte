<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlldudbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlldudbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-fill" {...props}></Icon>
