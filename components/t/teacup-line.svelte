<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wufu8db9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wufu8db9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:teacup-line" {...props}></Icon>
