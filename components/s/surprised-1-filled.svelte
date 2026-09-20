<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewlmo7vkk.css';
import '../../css/m/m3wlzfy-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewlmo7vkk"/><path class="m3wlzfy-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:surprised-1-filled" {...props}></Icon>
