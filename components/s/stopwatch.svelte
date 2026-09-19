<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrrw0tgug.css';
import '../../css/k/kh_vbgbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="rrrw0tgug"/><path class="kh_vbgbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:stopwatch" {...props}></Icon>
