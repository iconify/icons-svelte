<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvrty83tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvrty83tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:watch-vibrate" {...props}></Icon>
