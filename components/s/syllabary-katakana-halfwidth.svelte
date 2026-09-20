<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd-ebccqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd-ebccqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:syllabary-katakana-halfwidth" {...props}></Icon>
