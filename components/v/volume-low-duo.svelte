<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr1jw-bfg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c99v-pbvj.css';
import '../../css/r/rum0klbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr1jw-bfg secondary"/><g class="dt0cm9dhy primary"><path class="c99v-pbvj"/><path class="rum0klbyg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:volume-low-duo" {...props}></Icon>
