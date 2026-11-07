<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf8g6jb6t.css';
import '../../css/v/vhosuvb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf8g6jb6t"/><path class="vhosuvb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-2-bold" {...props}></Icon>
