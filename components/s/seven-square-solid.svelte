<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slvdg_bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slvdg_bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:seven-square-solid" {...props}></Icon>
