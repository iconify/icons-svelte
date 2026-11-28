<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmyai_b4a.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cc4luccci.css';
import '../../css/n/nxpnadcsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tmyai_b4a"/><g class="dt0cm9dhy primary"><path class="cc4luccci"/><path class="nxpnadcsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tree-duo" {...props}></Icon>
