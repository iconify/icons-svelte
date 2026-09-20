<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylwx14bgz.css';
import '../../css/w/w3xbe3b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylwx14bgz"/><path class="w3xbe3b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:snapchat" {...props}></Icon>
