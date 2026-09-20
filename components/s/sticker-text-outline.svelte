<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nua-p_ooz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nua-p_ooz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sticker-text-outline" {...props}></Icon>
