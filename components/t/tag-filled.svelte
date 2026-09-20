<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndo2xbcch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndo2xbcch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tag-filled" {...props}></Icon>
