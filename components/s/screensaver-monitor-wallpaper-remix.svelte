<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg2y4rbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cg2y4rbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:screensaver-monitor-wallpaper-remix" {...props}></Icon>
