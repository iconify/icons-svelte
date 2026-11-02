<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6yscct3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6yscct3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:server-line" {...props}></Icon>
