<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4-r16bpz.css';
import '../../css/c/c0abhhbxc.css';
import '../../css/b/bu3d-6cof.css';
import '../../css/x/xnmzdybto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4-r16bpz"/><path class="c0abhhbxc"/><path class="bu3d-6cof"/><path clip-rule="evenodd" class="xnmzdybto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallpaper-bold" {...props}></Icon>
