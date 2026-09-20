<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i36yhsbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i36yhsbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:to-do-line" {...props}></Icon>
