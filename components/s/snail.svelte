<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viyle3bdn.css';
import '../../css/i/isw4psbyy.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/j/j98506bch.css';
import '../../css/h/h36avfbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="viyle3bdn"/><path class="isw4psbyy"/><g class="ij2x_72vy"><path class="j98506bch"/><path class="h36avfbhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:snail" {...props}></Icon>
