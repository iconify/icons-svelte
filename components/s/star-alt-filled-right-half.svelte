<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2qt-w.css';
import '../../css/w/wtwpul.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-66.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2qt-w"/><path class="wtwpul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-alt-filled-right-half" {...props}></Icon>
