<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrcnysbjv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e77ebfb5e.css';
import '../../css/b/bdr6scb9e.css';
import '../../css/h/hqfrkub7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrcnysbjv secondary"/><g class="dt0cm9dhy primary"><path class="e77ebfb5e"/><path class="bdr6scb9e"/><path class="hqfrkub7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-power-duo" {...props}></Icon>
