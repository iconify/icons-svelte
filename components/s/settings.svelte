<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl3fapacx.css';
import '../../css/c/cerp886bk.css';
import '../../css/f/fdjy-kuog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yl3fapacx"/><path class="cerp886bk wm-a"/><path class="fdjy-kuog wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:settings" {...props}></Icon>
