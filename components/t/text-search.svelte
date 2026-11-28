<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o8acivbsi.css';
import '../../css/j/jzhyz-p4o.css';
import '../../css/j/j98qpqarz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="o8acivbsi"/><path class="jzhyz-p4o"/><path class="j98qpqarz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:text-search" {...props}></Icon>
