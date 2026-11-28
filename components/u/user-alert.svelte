<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/it6ujub8j.css';
import '../../css/j/jbjcviqqk.css';
import '../../css/j/jr68libbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="it6ujub8j"/><path class="jbjcviqqk"/><path class="jr68libbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-alert" {...props}></Icon>
