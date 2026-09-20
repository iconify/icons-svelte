<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vreafpbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vreafpbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sticker-square" {...props}></Icon>
