<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z09gg-b_z.css';
import '../../css/y/yncnjebzq.css';
import '../../css/w/woxdewbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z09gg-b_z"/><path class="yncnjebzq"/><path clip-rule="evenodd" class="woxdewbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-track-2-bold" {...props}></Icon>
