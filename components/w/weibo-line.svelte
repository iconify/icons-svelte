<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzo0zlbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzo0zlbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:weibo-line" {...props}></Icon>
