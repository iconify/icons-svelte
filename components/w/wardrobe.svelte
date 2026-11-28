<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n7r7azbdm.css';
import '../../css/a/af2wjebts.css';
import '../../css/w/w8cjkffza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n7r7azbdm"/><path class="af2wjebts"/><path class="w8cjkffza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wardrobe" {...props}></Icon>
