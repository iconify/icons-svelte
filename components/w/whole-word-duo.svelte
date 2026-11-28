<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nc6x_8gnc.css';
import '../../css/r/r_82qdbxl.css';
import '../../css/y/ym8-6c8tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nc6x_8gnc"/><path class="r_82qdbxl"/><path class="ym8-6c8tp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:whole-word-duo" {...props}></Icon>
