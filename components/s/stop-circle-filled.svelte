<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chsij3_2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chsij3_2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:stop-circle-filled" {...props}></Icon>
