<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5ukuz.css';
import '../../css/w/wtwpul.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-66.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ukuz"/><path class="wtwpul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-alt-twotone-half" {...props}></Icon>
