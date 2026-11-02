<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxqy_1fvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxqy_1fvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thermometer-fill" {...props}></Icon>
