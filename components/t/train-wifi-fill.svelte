<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqdjhp2zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqdjhp2zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:train-wifi-fill" {...props}></Icon>
