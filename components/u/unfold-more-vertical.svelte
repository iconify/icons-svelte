<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv0rdoajs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv0rdoajs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unfold-more-vertical" {...props}></Icon>
