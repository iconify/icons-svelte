<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df0yr2b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df0yr2b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sword-line" {...props}></Icon>
