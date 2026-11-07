<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z09gg-b_z.css';
import '../../css/a/absjoyb4u.css';
import '../../css/y/y1zrpxbtp.css';
import '../../css/w/wocmnefrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z09gg-b_z"/><path class="absjoyb4u"/><path class="y1zrpxbtp"/><path clip-rule="evenodd" class="wocmnefrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-track-bold" {...props}></Icon>
