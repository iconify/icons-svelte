<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1tb-nbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1tb-nbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:video-filled" {...props}></Icon>
