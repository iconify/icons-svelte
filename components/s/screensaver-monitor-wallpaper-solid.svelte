<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj3crfbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mj3crfbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:screensaver-monitor-wallpaper-solid" {...props}></Icon>
