<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp7upebym.css';
import '../../css/t/t_lvzblrs.css';
import '../../css/v/viyqlk6iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="xp7upebym"><path class="t_lvzblrs"/><path class="viyqlk6iu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:v" {...props}></Icon>
