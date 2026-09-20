<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab2wita7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab2wita7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:watch-vibrate-off" {...props}></Icon>
