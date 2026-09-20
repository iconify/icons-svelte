<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_hxwwbci.css';
import '../../css/m/m4fm11vel.css';
import '../../css/e/ezy_p22ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_hxwwbci"/><path class="m4fm11vel"/><path class="ezy_p22ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:task-time-filled" {...props}></Icon>
